docker_build('salman1091/tilt-demo', '.')
k8s_yaml('k8s-app.yaml')
k8s_resource('tilt-demo', port_forwards=8000)
allow_k8s_contexts('kubernetes-admin@kubernetes')
