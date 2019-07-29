# Gympass Mobile Challenge

## The problem

We have an API at the address `https://gympass-test.herokuapp.com`, which exposes a gym list resource as well as a checkin one. Your job is to develop an app that offers a complete checkin experience to the end-user. 

Feel free to create an experience that feels the most pleasant to the user.

The final user must be able to:

- View the gyms list;
- View all the activities of a given gym;
- Perform a checkin in a gym/activity.

## Walkthrough

- Use (preferentialy) react native for your application, avoiding Expo APIs usage;
- Use a state management solution if you need to;
- Try to use the most up to date Javascript features (ES6+);
- Write unit tests and any other tests you find helpful or important to have;
- Keep performance and corner cases in mind;
- Be creative and show us what you`ve got.

## The REST API

The API has two endpoints:

>- **GET** `/gyms` - returns a list of gyms with it`s activities.

>- **POST** `/checkin` - performs a checkin in a gym/activity.
>
>     Parameters:  
>     - `gymId` - Integer  
>     - `activityId` - Integer  

## Bonus

- Animations are welcome! 🤩
- Show gyms in some map view

## Delivery

- **Don't** fork this project. Create a new repository in your account and send us the URL;
- Create a README file with the instructions to run the project and the tests. Also add any comment that you think is relevant.

## What will be evaluated?

- Readability  
- Maintenance  
- Testabily
- Libs usage (Feel free!)

Thanks and good luck! 🍀