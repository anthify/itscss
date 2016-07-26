# itscss
A Sass (SCSS) starter project for large scale websites and applications using the ITCSS model.

Inspired by the creator of [ITCSS, Harry Robert](https://www.youtube.com/watch?v=1OKZOV-iLj4), and the [blog SCALABLE, MODULAR CSS by James Basoo](http://www.gpmd.co.uk/blog/scalable-css/)

ITCSS philosophy is based on the 'Inverted triangle of specifity'.
![alt text](https://hackpad-attachments.s3.amazonaws.com/hackpad.com_PIPWVUMv6rB_p.296099_1420807134466_itcss.jpg "The Holy Triangle!")

1. Settings: Global variables config switches (colours, screen sizes)
2. Tools: Functions and mixins
3. Generic: Ground-zero styles (normalize/reset.css, box-sizing)
4. Base: Unclassed HTML elements (type selectors)
5. Objects: Unstyled design patterns (media object)
6. Components: Styled objects, chunks of UI
7. Theme (optional): Themed components, used for multiple sites with the same layout and components. Can be utilised for multi-site Magento setups.
8. Trumps: Helpers and overrides, e.g. ```.float-left { float:left !important;}```

### Naming
It follows the [BEM naming convetion](http://csswizardry.com/2013/01/mindbemding-getting-your-head-round-bem-syntax/).
```.block {}
.block__element {}
.block--modifier {}```

Happy SCSS'in!
