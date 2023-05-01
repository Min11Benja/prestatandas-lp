# prestatandas-lp

Presta Tandas - is an online lonaning platform tool for people looking to join or run a Tanda. 

[Preview live website](http://prestatanda.com/)

## What is it: 

Tandas are a form of savings between friends, neighbours or coworkers who contribute an agreed upon amount of money to a weekly or monthly pool. These savings are then rotated between individuals in the group who either save this money or use it to make a major purchase that exceeds what they could normally afford.

## How do Tandas work?

- The host/person organizing the Tanda invites other people into a group, and ask them to join a Tanda for an X amount of money for N amount of time 
- Each member gives a fixed amount of money for an agreed amount of time
- Every time the money is collected, someone in the group is given the entire pot either randomly or through a schedule until every person in the group has received a pool (arrangements can be made for those needing emergency funds). 

For example, a tanda with eight people contributing $200 dollars monthly will take eight months to complete. This means at some point each member would receive a $1,600 lump sum.

## Why do people join tandas?

A tanda can occur anytime and is primarily used toward short-term savings goals. In Mexico, tandas are how millions of citizens pay for celebrations, emergencies or a way for people who may not have access to credit to meet their needs. For people who get the first numbers its a loan with 0% interest fee and for the people that get the last numbers in the turn, its more like a savings method but with accountability. Since the person HOST is the ones that makes sure you save money each week, you cant cheat yourself out of saving. 

## Installation

-  Download and install Node.js from nodejs.org (if you dont have it installed)
-  Clone the GitHub Repo with 
-  Start command prompt window or terminal and change directory to [ prestatandas-lp ] folder. 
```
git clone https://github.com/Min11Benja/prestatandas-lp.git 
cd prestatandas-lp
```
-  Run following command to install all the "dependencies and devDependencies". It could take few minutes to complete installation.
```
npm install
```
-  Run the following command to compile all the assets(sass, js, media) and copy HTML templates to a new folder called [dist] in same directory. (If you dont have GULLP installed please use this guide here to install it https://gulpjs.com/docs/en/getting-started/quick-start/)
```
gulp build
```
-  After you finished with above steps, run the following command to compile scss into css. it will keep running watch command to compile you edit.
```
gulp develop
```


## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
