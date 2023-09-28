# Contact-Form
Introducing our innovative contact form solution designed to enhance user accessibility on your HTML/CSS website. Say goodbye to the traditional method of displaying your contact email, and say hello to a more effective and user-friendly approach. With our custom contact form powered by Formspree, visitors to your website can effortlessly send messages directly to your inbox. Experience a seamless and modern way to connect with your audience while streamlining communication. Elevate your web presence with our contact form solution today.

## Installation
Use [Formspree](https://formspree.io) so the contact form can work completely fine.
1. Go to [Formspree](https://formspree.io)
2. Press Get started
3. Sign up with your email account if you want to receive mail from others. (Sign in if you already have an account.)
4. Click to create a project
5. Name your project and press create project
6. create your form inside your project
7. Once you created it, you should get ur URL
   For example:
```
Your form's endpoint is:
https://formspree.io/...
```
8. Copy URL and go to the code in section 12
9. Replace the URL in action with your URL and you're good to go
```html
<body>
    <form action="https://formspree.io/f/mdorpolj" method="POST">
        /* the code */
    </form>
</body>
```
