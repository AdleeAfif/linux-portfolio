# Web simulation of UbuntuOS

This is a personal portfolio website of theme Ubuntu 20.04, made using Next.js & tailwind CSS.
If you want to edit this. Clone this project and edit the files in `/src/components`.

To run this on localhost
type `npm start` and when u are done coding type `npm run build` to build your app.

_NOTE: if you have yarn just replace `npm start` and `npm run build` with `yarn start` and `yarn build`._

<a href="https://buymeacoffee.com/adleeafif" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 40px !important;width: 140px !important;" ></a>

### To make the contact form work

- Create a account in [emailjs](https://www.emailjs.com/) create also new Outlook or Gmail account to be able
  to send email.
- Create a new service, select and log in to your newly created outlook or gmail account on EmailJS.
- Go back to the dashboard and get the Service ID copy it.
- Create a .env file in your root folder and put

```

NEXT_PUBLIC_USER_ID = 'YOUR_USER_ID'
NEXT_PUBLIC_TEMPLATE_ID = 'template_fqqqb9g'
NEXT_PUBLIC_SERVICE_ID = 'YOUR_SERVICE_ID'

```

into it. Replace \*your user id and your service ID with your values in your EmailJS service.

## Credit/Disclaimer

This project is a fork of an original repository. I would like to acknowledge and credit the original creator for their amazing work on this Linux-style portfolio website.

**Original Repository:** [Link to original repo if available]

This fork maintains the core functionality and design while adding my own modifications and improvements. The original creator's work serves as the foundation for this project, and I am grateful for their contribution to the open source community.

If you are the original creator and would like me to add proper attribution or make any changes, please feel free to reach out.
