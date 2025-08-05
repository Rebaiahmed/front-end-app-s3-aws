# Vue 3 + Vite + AWS S3 Deployment

This is a Vue 3 app built with Vite, deployed to **AWS S3** and **CloudFront** using **GitHub Actions**.

## Deployment

- Push to `main` → GitHub Actions builds and deploys to S3
- CloudFront cache is automatically invalidated

## Setup

- Configure AWS credentials in GitHub secrets:
  - `AWS_ACCESS_KEY_ID`
  - `AWS_SECRET_ACCESS_KEY`
  - `DISTRIBUTION_ID`
- Update bucket name in the workflow file

## Resources

- [Vue 3 Docs](https://vuejs.org/)
- [S3 Static Hosting](https://docs.aws.amazon.com/AmazonS3/latest/userguide/WebsiteHosting.html)
- [GitHub Actions](https://docs.github.com/en/actions)
