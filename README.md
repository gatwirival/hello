# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
```jsx
import { Box } from "@prismane/core";

const Page = () => {
  return (
    <>
      <Box bg="diamond">Hello, world</Box> // Prismane Color
      <Box bg="primary">Hello, world</Box> // Theme Color
      <Box bg={(theme) => (theme.mode === "dark" ? "primary" : "base")}>
        Hello, world
      </Box>
      <Box bg={["primary", { hover: "base" }]}>Hello, world</Box> // Pseudo Class
      <Box bg="#ffffff">Hello, world</Box> // Custom Color
    </>
  );
};

export default Page;
```
