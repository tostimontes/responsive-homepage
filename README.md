# Responsive Website

This repository contains my work for the Odin Project's Advanced HTML and CSS course. The primary objective of this project was to design and implement a responsive website suitable for three different screen sizes, using only HTML and CSS. The project was approached with a mobile-first development strategy, ensuring that the website is fully functional and aesthetically pleasing on mobile devices, tablets, and desktops.

## Project Overview

Feel free to visit at [Responsive Homepage](https://tostimontes.github.io/responsive-homepage/) by *[tostimontes](https://github.com/tostimontes)*
![Overview](./media/overview.gif)

### Mobile-First Approach

The mobile-first approach is evident in the CSS where media queries are used to scale up the design for larger screens. This strategy helps in optimizing the website for mobile devices initially and then gradually enhancing the layout for larger screens.

To achieve a responsive design, I have utilized CSS media queries that adapt the website's layout to different screen sizes. The breakpoints are set at 768px and 1024px, corresponding to tablet and desktop screen sizes, respectively. This ensures a seamless transition and a consistent user experience across various devices.

### Highlights

- **Layout Techniques**: Usage of Flexbox and CSS Grid to create flexible and grid-based layouts, evident in classes like `.hero` and `.cards-grid`.
- **Pseudo-elements**: Usage of `body::before` to create interesting visual effects like angled backgrounds.
- **Responsive Typography**: Font sizes are adjusted in media queries to ensure readability and aesthetic appeal on larger screens.
- **Image CDN**: For hosting and serving the images efficiently, I have integrated Cloudinary, a cloud-based service that provides solutions for image and video management. It allows for easy upload, storage, manipulation, and delivery of images across different devices with optimal loading times.

## Future Improvements

While the current implementation provides a solid foundation, the following enhancements could be considered:

1. **Semantic HTML**: Incorporate more semantic HTML tags to improve the website's structure and accessibility.
2. **Optimization with more breakpoints**: Introduce additional breakpoints to cater to a wider range of screen sizes. This will involve defining styles for smaller screens to enhance readability and navigation on devices like smartwatches and smaller smartphones. Similarly, for very large screens, such as 4K monitors, implement further layout refinements to utilize the available screen real estate effectively, ensuring content is not overly stretched or spaced.
3. **Performance Optimization**: customize image sizes and quality only using Cloudinary's tags.

## Credits
- Images
    - Working1: Photo from cottonbro studio: [Pexels Link](https://www.pexels.com/es-es/foto/hombre-escritorio-ordenador-portatil-oficina-4064840/)
    - Working2: Photo from cottonbro studio: [Pexels Link](https://www.pexels.com/es-es/foto/hombre-escritorio-ordenador-portatil-oficina-4064839/)
- Iconography
    - [Devicon.dev](https://devicon.dev/) for programming-related icons.
    - [Material Design Icons](https://pictogrammers.com/library/mdi/) for other icons.