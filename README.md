To enable Ansible Content Creators and Ansible Platform Administrators to take advantage of automation execution environments, ansible-builder was created, which aids in the creation of execution environments.

ansible-builder build -v3 -t custom-ee



v3 - is to add verbosity to the cli run, for the user to check what is happening with each build of execution environment
-t custom-ee - will tag your image name as custom-ee The build takes around 2-4 minutes, please check the command logs to see what's happening behind the scenes meanwhile

use the below command to check the image list via podman

podman images
