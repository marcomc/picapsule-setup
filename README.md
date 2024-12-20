# PiCapsule Workspace

This workspace environment is designed for PiCapsule. Below are the available commands and their descriptions.

## Commands

### `ws enable %`

Enables the specified service.

- **Parameter**: `%` - The service to enable.

### `ws rebuild %`

Rebuilds and recreates the specified service.

- **Parameter**: `%` - The service to rebuild.

### `ws disable`

Disables all services.

### `ws destroy`

Destroys all services, removes images, volumes, and orphans with a timeout of 120 seconds.

### `ws console`

Opens a bash console in the ansible container.

### `ws ansible-playbook <playbook> <inventory> %`

Runs an Ansible playbook with the specified inventory and additional parameters.

- **Parameter**: `%` - Additional parameters for the playbook.
- **Playbook**: `<playbook>` - The playbook to run.
- **Inventory**: `<inventory>` - The inventory file to use.

### `ws ansible-galaxy install %`

Installs Ansible roles from the requirements file with additional parameters.

- **Parameter**: `%` - Additional parameters for the installation.

### `ws ansible-lint`

Runs Ansible lint on the ansible directory.

### `ws welcome`

Displays a welcome message with URLs for Cockpit, Pi-Hole, and AFP Path.

- **Cockpit URL**: `http://<raspberry_pi_ip>:9090`
- **Pi-Hole URL**: `http://<raspberry_pi_ip>/admin`
- **AFP Path**: `afp://<raspberry_pi_ip>/afpshare`