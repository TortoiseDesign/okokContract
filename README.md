Hi, thank you for use my script, I'm very grateful!

If you need help contact me on discord: Tortoise Design#9228 Discord server: https://discord.gg/3GFKFPaxK3
1. Go to your database and execute the following SQL command:

INSERT INTO `items` (`name`, `label`, `weight`) VALUES ('contract', 'Contract', 1);


2. To change the vehicle name that appears on the contract, navigate to the vehicle folder and open the file 'vehicles.meta', you should change the <gameName>.

Example:
<gameName>Nissan GT-R</gameName>

3. If you use the latest qb-core version make sure to change the 'exports['ghmattimysql']:execute' in the server side to 'exports.ghmattimysql.executeSync'!
