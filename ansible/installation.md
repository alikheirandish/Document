# Ansible Installation

`Install python 3.9 on your system`

`python3.9 -m venv PATH/TO/VENV`

`source PATH/TO/VENV/bin/activate`

`pip install ansible`

`pip install yamllint`

`pip install ansible-lint`

`pip install molecule[docker]`

to create a new role run:

`molecule init role myrole`

`molecule test`

`molecule converge`

`molecule verify`

`molecule login`

`molecule destroy`

`molecule init scenario`
