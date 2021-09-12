# Fix for error when starting SonarQube container (original value was vm.max_map_count = 65530):

sysctl -w vm.max_map_count=262144
