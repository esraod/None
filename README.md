# u11-fullstack-js-esraod

~ *Esra Oktav [2020/08/15]*

</br>
_In memory of my dog Bamse_

</br>

## The Idea
Creating a waterlevel sensor that works with a raspberry pi zero to show the current water level of my dogs water bowl and log it, using
using MERN (MongoDB, Express, React.js, node.js)
</br>
#### Stack
- **M**ongoDB
- **E**xpress
- **R**eact.js
- **N**ode.js
- Python
</br>

#### Task Goals
- Show precetage of the water level.
- Log the water level.
- Working on *several* web browsers and devices (both on desktop and mobile).
- Responsive (Should work to use on *every* devices).
</br>


--------------

## How to run it


1. Clone the repo
```
git clone https://github.com/chas-academy/u11-fullstack-js-esraod.git
```
</br>

2. Setup and install backend 
  ```
  cd backend
  npm install
  ```
Then Setup MongoDB
using MongoDB locally or using MongoDB Atlas. 
</br>
Change the url in backend/index.js on line 13,

```
mongoose.set('useFindAndModify', false);
mongoose.connect(
  '[Replace this with the url]',
  { useNewUrlParser: true }
);
```

</br>

3. Install packages 
```
cd frontend
npm install
```
</br>

4. Run the backend

```
cd backend
npm run start
```
</br>

5. Run the view/frontend

```
cd frontend 
npm run start
```


## Result 
-----------------

![waterlevel](waterlevel.png)


</br>

#### Future Extra Challanges:
- [ ] Notifications to mobile when the water level reaches a certain level.
- [ ] Water level shown visually.
</br>

### Author
**Esra Oktav**

- github/
[esraod](https://www.github.com/esraod) :octocat:



-------------------------------------------------------
2020
