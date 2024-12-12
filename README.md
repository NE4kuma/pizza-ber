![2024-10-14_22-39](https://github.com/user-attachments/assets/ddb16829-af5a-4b6f-aa25-980faf52dff8)
### Pizza Website with Shopping Cart
Here is a website with several dishes, with a shopping cart... for a schoolproject, because of that it also have some german words. <br>
**Warning**: This project is designed for learning purposes only. It is not intended for professional use and is suitable for school or study projects.

## Intallation
(If you want to host this webshop, make sure it is only for local network usage.) <br>
Before we begin, we need to install the necessary packages:
```bash
sudo apt install apache2 git
```
**Notice:** If you're using a different Linux distribution, make sure to use the correct `package manager`. The steps should be similar across distributions.<br>
Now go to the weblocation and install the rigt respetory:
```bash
cd /var/www/html
sudo git clone git@github.com:Ne4ec/Webshop-pizza.git
```
Put everything in the weblocation and remove the unused folders:
```bash
mv Webshop-pizza/* .
rm -rf Webshop-pizza/
```
One last command, and with that, we start the web server:
```
systemctl start apache2
```
After that, your website should be up and running! You can open your browser and navigate to:
```
http://localhost
```
It should appars some pruduct :).

### Important:
This project was created by me, and I drew inspiration from a few helpful websites:
<li>https://github.com/nikmace/pizza-shop</li>
<li>https://cssgradient.io/</li>
<li>https://pngtree.com/</li>
<li>https://www.pngwing.com/</li>
<li>https://webcode.tools/css-generator/background-gradient</li> <br>
These websites provided inspiration, but no code was copied directly. 

## Conculution
Hopefully, everything is working. If not, please leave a comment in the Issues tab. Thank you for paying attention, and have a nice day :)<br>
~ NeSec
