# Description

---

A full-stack ecommerce website that allows buyers to browse products, filter them by available categories, add products to their shopping cart, and purchase products.

# Tech Stack

---

**Front-end**

- [React](https://reactjs.org/)
- [React Router](https://reactrouter.com/)
- [Redux Toolkit](https://redux-toolkit.js.org/tutorials/quick-start)
- [Material UI](https://mui.com/core/)
- [Formik](https://formik.org/docs/overview)
- [Yup](https://github.com/jquense/yup)
- [Stripe JS](https://stripe.com/docs/js)
- [React Responsive Carousel](https://www.npmjs.com/package/react-responsive-carousel)

**Backend**

- [Node.js](https://nodejs.org/en/)
- [Strapi](https://docs.strapi.io/)
- [Stripe](https://stripe.com/docs)
- [Dotenv](https://www.npmjs.com/package/dotenv)

# Usage

---

1. **Clone this repository**

```
git clone https://github.com/rebkang/e-commerce-app.git
```

2. **Create Stripe account and retreive the secret key**

3. **Env variable**
   Create a .env file in the server directory and add the following:

```
HOST = 0.0.0.0
PORT = 1337
APP_KEYS = "toBeModified1,toBeModified2"
API_TOKEN_SALT = tobemodified
ADMIN_JWT_SECRET = tobemodified
JWT_SECRET = tobemodified
STRIPE_SECRET_KEY = tobemodified
```

4. **Client**

```
cd client
npm install
npm start
```

5. **Server**

```
cd server
npm install
npm run develop
```
