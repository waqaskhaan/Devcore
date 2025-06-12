DevCore
DevCore is a Vagrant-powered, multi-VM infrastructure project that simulates a real-world 5-tier architecture. It includes:

MySQL (db01) – Database layer
Memcached (mc01) – Caching layer
RabbitMQ (rmq01) – Messaging layer
Tomcat (app01) – Java app server
Nginx (web01) – Web proxy layer

Each VM is auto-provisioned with shell scripts and configured to work together seamlessly, making it perfect for:

DevOps practice & automation
Local development & testing
CI/CD pipeline simulation

Runs on VirtualBox + Vagrant, and supports Windows, macOS (Intel), and Linux.
