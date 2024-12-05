# Findings

## 1. SQL Injection

### Description
A sql injection was found in the user creation functionality. This can be exploitable via the username field in the create user functionality or via the rest api used by the ui.

### Source
User.py:create_user:L31

### Ease of Exploitation
Very easy. Any standard test such as `'); SELECT * users; --`

### Likelyhood of Exploitation
Very likely as user creation is a public facing function

### Risk
High

This is a high risk finding as it can lead to sensative information being exposed. It is very easy to exploit due to being public facing functionality thus elevating the risk of this finding.

### Recommendation
Do not use string concatenation for sql queries and use a orm/framework that sanitizes queries such as SqlAlchemy
