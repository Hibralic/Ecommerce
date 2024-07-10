# Ecommerce

# Hasko's House

Welcome to Hasko's House! This project is a web-based furniture store that allows users to browse products, add them to their cart, and manage their purchases. The site is built with HTML, CSS, and JavaScript, leveraging Contentful for content management.


## Demo

You can check out a live demo of the project [here](https://vanilla-js-shoppingcart-hasko.netlify.app/).

## Features

- Responsive design
- Product listing
- Shopping cart functionality
- Integration with Contentful for product management

## Technologies Used

- HTML
- CSS
- JavaScript
- Contentful (for content management)
- FontAwesome (for icons)

## Installation

To get a local copy up and running, follow these simple steps:

1. Clone the repo

```sh
git clone https://github.com/Hibralic/Ecommerce.git
```

2. Open the `index.html` file in your browser to view the site.

## Usage

This project uses Contentful to manage product data. To set it up:

1. Create a Contentful account and set up a space.
2. Add a content type named `comfyHouseProduct` with fields for `title`, `price`, and `image`.
3. Replace the `space` and `accessToken` in the `app.js` file with your Contentful credentials.

```javascript
const client = contentful.createClient({
  space: "your_space_id",
  accessToken: "your_access_token",
});
```

## Content Management

This project fetches product data from Contentful. To add products, log in to your Contentful account and create entries for the `comfyHouseProduct` content type.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Acknowledgements

- [FontAwesome](https://fontawesome.com/)
- [Contentful](https://www.contentful.com/)

Thank you for visiting Hasko's House! If you have any questions or suggestions, feel free to open an issue or create a pull request.
