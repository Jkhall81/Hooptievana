# Hooptievana

Hooptievana is a car rental web application built with Next.js, TypeScript, Tailwind CSS, and Headless UI. It utilizes APIs for car detail content and car images to provide users with a platform to search vehicles based on make, model, fuel type, and vehicle year. The site also includes a show more pagination feature and is fully responsive.

## Features

- Vehicle Search: Users can search for vehicles using a combination of make, model, fuel type, and vehicle year.
- Search Filters: Users can apply filters for fuel type and vehicle year to narrow down their search results.
- Car Detail Modals: The application integrates with APIs to provide detailed information about each car.
- Car Images: The application retrieves car images from APIs to display alongside the car details.
- Show More Pagination: Users can browse through paginated results and load more vehicles as they scroll.
- Responsive Design: The site is fully responsive and optimized for different screen sizes.

## Technologies Used

- Next.js: The React framework used for server-side rendering and building the web application.
- TypeScript: The programming language used for type-checking and improved code reliability.
- Tailwind CSS: The utility-first CSS framework used for responsive and customizable styling.
- Headless UI: The UI components library used for building accessible and customizable user interfaces.
- Deployed on Vercel

## Seup

1. Clone the repository:

   ```
   git clone https://github.com/Jkhall81/Hooptievana.git
   ```

2. Navigate to the project directory:

   ```
   cd Hooptievana
   ```

3. Install dependencies:

   ```
   npm install
   ```

4. Run the development server:

   ```
   npm run dev
   ```

## Dependencies

- @headlessui/react: Version ^1.7.15
- @types/node: Version 20.4.1
- @types/react: Version 18.2.14
- @types/react-dom: Version 18.2.6
- autoprefixer: Version 10.4.14
- eslint: Version 8.44.0
- eslint-config-next: Version 13.4.9
- next: Version 13.4.9
- postcss: Version 8.4.25
- react: Version 18.2.0
- react-dom: Version 18.2.0
- tailwindcss: Version 3.3.2
- typescript: Version 5.1.6

## Known Issues

Car Images: There is currently a bug with retrieving car images from the APIs. Ensure that the necessary APIs are configured correctly and that the image retrieval logic is implemented accurately.

## License

MIT License
