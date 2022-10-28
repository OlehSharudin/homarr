# homarr
Homepage with apps for using less chrome tabs.

## Requiremnts:

Docker

## Install and Maintenance

To run simply download files, open powershell prompt from folder and run: 

> docker compose up -d

Open browser and open:

> localhost:7575

If you see a bar about an updated version available (and you're very annoyed by it), you can redeploy container with new image:

> docker compose down<br/> 
> docker rmi ghcr.io/ajnart/homarr<br/> 
> ndocker compose up -d
