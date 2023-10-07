## Private docker registry with UI
<b>Resources:</b>
* ``joxit/docker-registry-ui`` for UI 
* ``registry:2`` for private registry

### Create password for registry
First check if OS for ``apache2-utils`` via executing ``htpasswd`` command in terminal. If not installed follow execute command below:<br>
``sudo apt install apache2-utils``
1. Execute ``htpasswd -Bc htpasswd my_username``
2. Then input password

