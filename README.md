1- Enter the config file for nano $HOME/.kujira/config/config.toml. This command is made .kujira for kujira, .sei for sei, .defund for defund, .stafihub, haqq....
## /root/.kujira/config/config.toml

a- We find proxy_app port in config.toml file. By default it uses port 26658. Let's change it to 36658.
![proxty](https://user-images.githubusercontent.com/98549582/186489610-95cdf375-d6f6-4e11-aa59-61dccf1b54c3.PNG)

b- We find the laddr port in the config.toml file. By default it uses port 26657. Let's change it to 36657.
![ladddr](https://user-images.githubusercontent.com/98549582/186489747-df697e2c-1b3a-4aee-a669-cd2250349420.PNG)

c- We find the pprof_laddr port in the config.toml file. By default it uses port 6060. Let's change it to 7060.
![prof](https://user-images.githubusercontent.com/98549582/186489797-964715f1-aca8-41e9-94af-36e390d0bf28.PNG)

d- We find a second laddr port in the config.toml file. By default it uses port 26656. Let's change it to 36656.
![laddr2](https://user-images.githubusercontent.com/98549582/186489905-aa3bbdd6-cae1-4c6a-b418-1814dcb56b76.PNG)

e- We find the prometheus_listen_addr port in the config.toml file. By default it uses port 26660. Let's change it to 36660.
![promot](https://user-images.githubusercontent.com/98549582/186489974-1b399d7b-ec5e-4351-9759-7a19b8c46b16.PNG)

2- We enter the file with nano $HOME/.kujira/config/app.toml command. This command is made in the form of .kujira for kujira, .sei for sei, .defund for defund, .stafihub, haqq...

## root/.kujira/config/app.toml

a- We find the address port in the app.toml file. By default, port 9090 is used. Let's change it to 10090.
![address](https://user-images.githubusercontent.com/98549582/186490157-ead15122-2c86-4d51-a021-13e28a587f4b.PNG)

b- We find a second address port in the app.toml file. By default, port 9091 is used. Let's change it to 10091.
![address2](https://user-images.githubusercontent.com/98549582/186490210-42f52d5a-3570-4bfd-bb8b-73c7d39a756c.PNG)

3- We enter the file with nano $HOME/.kujira/config/client.toml command. This command is made in the form of .kujira for kujira, .sei for sei, .defund for defund, .stafihub, haqq...

## root/.kujira/config/client.toml

a- We find a second node port in the client.toml file. By default, port 26657 is used. Let's change it to 36657.
![node](https://user-images.githubusercontent.com/98549582/186490324-e68de88b-f264-48e3-96ce-b69d1b81166a.PNG)
