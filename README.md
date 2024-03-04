<p align="center">
    <img src="https://www.sba.gov/brand/assets/sba/img/pages/logo/variations-horizontal-one-color-reversed.svg" height="130">
</p>
<p align="center">
    <a href="https://nextjs.org/" alt="NextJS">
        <img src="https://img.shields.io/badge/next%20js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" /></a>
    <a href="https://react.dev/" alt="ReactJS">
        <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" /></a>
</p>

# UCMS Frontend App

## Getting Started
- [UX/UI Guide](https://github.com/USSBA/ucms-developers/tree/UX-UI-CX)
- [Microservices Prototype Learning Path](https://github.com/USSBA/ucms-developers/tree/learning-paths/ms_prototype)

## Stacks

### backend

- FastAGI

### frontend

- [Next.js]
- [React.js]

## Quickstart
First, install dependencies

```bash
yarn
```
Last, run the common Next.js script to start

```bash
yarn dev
```

## Deployment with Docker
You must have [docker] and [docker-compose] tools installed to work with the material in this section. The just run:

```
docker-compose up -d app
```

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.

---

**Other Repositories**

<div id="user-content-toc">
  <ul>
    <li><a href="#1-for-the-developer">Repositories</a>
      <ul>
        <li><a href="https://github.com/USSBA/ucms-backend-app">Django Microservices</a></li>
        <li><a href="https://github.com/USSBA/ucms-wfe-app">ReactJS and NextJS Frontend Application</a></li>
        <li><a href="https://github.com/USSBA/ucms-internal-api">FastAPI Internal API</a></li>
        <li><a href="https://github.com/USSBA/ucms-external-api">Flask External API</a></li>
        </li>
      </ul>
    </li>
  </ul>
</div>

---

<!--  Create .env.local file for Okta Authentication - valid for 30 days

// .env.local
OKTA_OAUTH2_CLIENT_ID="0oafiethqhceYykDl5d7"
OKTA_OAUTH2_CLIENT_SECRET="mqrjSyyjMK4vIx7O7UCFHom_qtcpOvUNxi3dYram9TJa-3ImsS39GQuZr_fzDfuk"
OKTA_OAUTH2_ISSUER="https://dev-76475091.okta.com/oauth2/default"
NEXTAUTH_URL=http://localhost:8080
SECRET=EBD5AA96E7CCEF4C41CF7442C41CC 

--------------------------------------------------
 > Setps to Create a Okta .env File 
 
okta apps create

Create your app with okta apps create
1.Take the default app name or rename if you would like
2.Choose the Web option for the Type of Application
3.Choose Other for the Framework of Application
4.Redirect URI: http://localhost:8080/api/auth/callback/okta
5.Logout Redirect URI: http://localhost:8080

Reference:
https://thetombomb.com/posts/nextjs-nextauth-okta

-->
