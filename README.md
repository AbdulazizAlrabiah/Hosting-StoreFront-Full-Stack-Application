# Hosting-StoreFront-Full-Stack-Application

## Table of Contents

- [Description](#Description)
- [Screenshots](#Screenshots)
- [References](#References)

## Description
This is a full stack application written in TypeScript to serve a small E-commerce prototype. It allows users to create an account, view products and view cart. Users can also add products to their cart and checkout. The application is hosted on AWS and accessible [here](http://store-front-frontend-production.s3-website-us-east-1.amazonaws.com).

The full stack application is split into two repositories (Frontend and Backend). Each with their own CI/CD pipeline and configuration (E.x: package.json).

## Screenshots

- Running S3 Bucket:
![Running S3 Bucket](Assets/Healthy_S3.png)

- ٍRunning EB Environment:
![Running EB Environment](Assets/Healthy_EB.png)

- Running RDS Database:
![Running RDS Database](Assets/Healthy_RDS.png)

- Frontend CI/CD Pipeline:
![Frontend CI/CD Pipeline](Assets/Frontend_Successful_CI-CD.png)

- Backend CI/CD Pipeline:
![Backend CI/CD Pipeline](Assets/Backend_Successful_CI-CD.png)

- CircleCI Environment Variables:
![CircleCI Environment Variables](Assets/CircleCi_ENV_VARS.png)

## References

[Documentation](./Documentation)

[Configurations files](./Configurations)

[Frontend Repository](https://github.com/AbdulazizAlrabiah/Storefront-Frontend)

[Backend Repository](https://github.com/AbdulazizAlrabiah/Storefront-Backend)