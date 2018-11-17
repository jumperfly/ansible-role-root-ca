# Root Certificate Authority Ansible Role
Generate and manage root CA certificates.

## Configuration
| Key | Description |
|-----|-------------|
| root_ca_base_dir            | Location to store keys, csrs, certificates. |
| root_ca_expiry_years        | Root CA certificate validity in years. |
| root_ca_subject | A dict object containing all attributes of the certificate subject (see defaults/main.yml). |
