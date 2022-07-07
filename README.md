### Adaptive Online Store of goods for pets 🐶🏠

#### React (React Roating, React Hooks), Redux (Thunk), Formik, Yup, SCSS, CSS modules


*📝The project is still in development*

*At the end of the file you can find features which i want to add*

[Live Demo](https://online-shop-react-mu.vercel.app/)

### 📚About the project

Online store of houses for pets consists of 4 pages:
- Home (Catalog);
- Cart;
- Favorites;
- 404;

#### 💻 Home page
![image] ![image](https://user-images.githubusercontent.com/86040508/177772359-c6d2c8bc-aab1-45f8-9532-ef20010acf02.png)

---
#### 🛒 Cart page
![image]![image](https://user-images.githubusercontent.com/86040508/177772485-66e733fe-6524-4be2-84b6-488e609429cf.png)

---
#### ⭐️ Favourite page
![image]![image](https://user-images.githubusercontent.com/86040508/177772530-09580d81-d499-44fc-a5f9-b712fb484964.png)

---
#### 🔎 404 page
![image](https://user-images.githubusercontent.com/68449997/140306025-9063cbd2-b0d0-478a-81a9-c2aaf1b8d46b.png)

---

#### 📘Functional:
- interaction with the cart (adding and removing products);
- interaction with favorites (adding and removing products);
- synchronization of products in the cart, favorites, discount(by entering promocde before purchase) with the Local storage;
- clarifying modal windows before adding and removing products;
- showing skeleton loader using `react-content-loader`;
- substitute the default image if the product doesn`t have photo;
- selection products` count in the cart and calculation of the total amount of this product;
- block with general information about the order, the total amount;
- the ability to enter a promotional code for a specific discount;
- get guest promocode by clicking on the animated dog;

<img src="https://user-images.githubusercontent.com/68449997/139599093-54e25a8a-697a-429f-a675-58fd1f21b689.png" height="150">

- checkout modal with information about the order and customer (if there is a lot of information in the modal window, it can be scrolled);
- form of order data information (name , number , where and how to deliver) with validation;
- unit tests of most used components: modal and buttons, using Jest and testing-library;

#### 🎥 App video demo:

https://user-images.githubusercontent.com/68449997/139599195-04bb8141-513f-459d-a7bc-87badf1f7de8.mp4



#### 📒The following features are planned to be added:
- page of 1 product;
- main page with slider;
- change skeleton loader grid on mobile devices
