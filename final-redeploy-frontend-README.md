Required Variables to paas in playbook:
nexus_url
project_name
site_name ( can write same as project_name)
site_url ( for health status check )

For IIS site Creation:
required:
host_port (default 80)
host_ip (default '*')
host_name (default omit)


for https Bindings:
required:
ssl_cert_thumbprint
optional:
https_port (default 443)
host_ip (same with site creation) (default '*')
host_name (same with site creation) (default omit)
