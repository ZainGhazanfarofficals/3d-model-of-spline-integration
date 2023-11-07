# Integrating a Spline 3D Model with React

In this guide, we will walk you through the process of integrating a Spline 3D model into a React application. The `@splinetool/react-spline` library makes it easy to embed Spline 3D models within your React application.

## Prerequisites

Before you begin, make sure you have the following tools and libraries installed:

- [Node.js](https://nodejs.org/) for managing packages and running your React application.
- [React](https://reactjs.org/) for building the user interface.
- [Spline 3D model scene URL generated from Spline](https://www.spline.design/) platform.

## Step 1: Set Up Your React Project

If you don't have a React project yet, create one using `create-react-app` or your preferred setup. Navigate to your project directory and install the necessary dependencies:

```bash
npm install @splinetool/react-spline
```
## Step 2: Integrate the Spline 3D Model

In your React component, import the `@splinetool/react-spline` library and use the `Spline` component to embed your Spline 3D model. Provide the URL of your Spline scene as a prop to the `scene` attribute.
