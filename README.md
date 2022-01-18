# ec2_ssh
## Setup
1. Project Settings >> Additional SSH Keys >> add instance private-key & ip/hostname
2. Project Settings >> Environment Variables >> SSH_USER="", SSH_HOST=""
3. Run command (on config.yml) with     ssh $SSH_USER@$SSH_HOST "command"

check
ssh -o IdentitiesOnly=yes -i key.pem user@host