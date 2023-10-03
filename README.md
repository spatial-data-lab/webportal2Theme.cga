# webportal2Theme.cga

## how to install 

1. download this repo and move it into the config directory

```bash
cd /opt/knime/knime_server_4.16/workflow_repository/config
git clone https://github.com/spatial-data-lab/webportal2Theme.cga.git
```

2. change the configure file `/opt/knime/knime_server_4.16/workflow_repository/config/knime-server.config`

change the following line 
```
com.knime.server.webportal2.theme_folder=webportal2Theme.cga
```
