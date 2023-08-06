<a name="readme-top"></a>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/benjisoft/react-particle-animation">
    <img src="https://visimedia.co.uk/images/Logo-Horizontal-Transparent-p-500.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">React Particle Animation</h3>

  <p align="center">
    A simple library to provide react compatible particle animations. Forked from https://github.com/transitive-bullshit/react-particle-animation. 
    <br />
    <a href="https://github.com/benjisoft/react-particle-animation"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://transitive-bullshit.github.io/react-particle-animation">View Demo</a>
    ·
    <a href="https://github.com/benjisoft/react-particle-animation/issues">Report Bug</a>
    ·
    <a href="https://github.com/benjisoft/react-particle-animation/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![React Native Animation Screen Shot][product-screenshot]](https://github.com/benjisoft/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [![React][React.js]][React-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



## Install

```bash
npm install --save react-particle-animation
# or
yarn add react-particle-animation
```

## Usage

Check out the [demo](https://transitive-bullshit.github.io/react-particle-animation/) in the [example folder](https://github.com/transitive-bullshit/react-particle-animation/tree/master/example).

```jsx
import React, { Component } from 'react'

import ParticleAnimation from 'react-particle-animation'

class Example extends Component {
  render () {
    return (
      <ParticleAnimation />
    )
  }
}
```

## Props

| Property      | Type               | Default                               | Description                                                                                                                                  |
|:--------------|:-------------------|:--------------------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------|
| `numParticles`  | number           | 400                                  | Number of particles to use. |
| `interactive`   | boolean          | true                                 | Whether or not animation responds to mouse hover. |
| `color`         | object           | { r: 158, g: 217, b: 249, a: 255 }   | Base rgba particle color. |
| `background`    | object           | { r: 255, g: 255, b: 255, a: 255 }   | Background rgba color. |
| `lineWidth`     | number           | 1.0                                  | Connecting line width. |
| `particleRadius`| number           | 1.0                                  | Scaling factor for particle radii. |
| `particleSpeed` | number           | 1.0                                  | Scaling factor for particle speed. |
| `...`           | ...              | undefined                            | Any other props are applied to the root canvas element. |

Note that for colors, `rgba` are all floating point numbers between 0 and 255 (inclusive).

Note that the canvas size will automatically be inferred based on available space via [react-sizeme](https://github.com/ctrlplusb/react-sizeme), so it should be really easy to use this component as a fullscreen background as in the [demo](https://transitive-bullshit.github.io/react-particle-animation/).

## Related

- [particles.js](https://github.com/VincentGarreau/particles.js) - Older particle animation. Oddly enough, I developed this animation in Java back in 2008, though the two animations are AFAIK unrelated to each other.
- [Intersection.Aggregate](http://www.complexification.net/gallery/machines/interAggregate/index.php) - Jared Tarbell's original processing work from 2004 which this animation was inspired by (e.g., visualizing the intersections between circles moving about randomly).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Ben Lewis - [@benjisoft](https://twitter.com/benjisoft) - ben.lewis@visimedia.co.uk.com

Project Link: [https://github.com/benjisoft/react-particle-animation](https://github.com/benjisoft/react-particle-animation)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [transitive-bullshit](https://github.com/transitive-bullshit/react-particle-animation)
* [othneildrew](https://github.com/othneildrew/Best-README-Template)
* [VisiMedia](https://visimedia.co.uk)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/benjisoft/react-particle-animation.svg?style=for-the-badge
[contributors-url]: https://github.com/benjisoft/react-particle-animation/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/benjisoft/react-particle-animation.svg?style=for-the-badge
[forks-url]: https://github.com/benjisoft/react-particle-animation/network/members
[stars-shield]: https://img.shields.io/github/stars/benjisoft/react-particle-animation.svg?style=for-the-badge
[stars-url]: https://github.com/benjisoft/react-particle-animation/stargazers
[issues-shield]: https://img.shields.io/github/issues/benjisoft/react-particle-animation.svg?style=for-the-badge
[issues-url]: https://github.com/benjisoft/react-particle-animation/issues
[license-shield]: https://img.shields.io/github/license/benjisoft/react-particle-animation.svg?style=for-the-badge
[license-url]: https://github.com/benjisoft/react-particle-animation/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/benji-lewis
[product-screenshot]: https://github.com/benjisoft/react-particle-animation/blob/master/demo.png?raw=true
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 

## License

MIT © [transitive-bullshit](https://github.com/transitive-bullshit)

This module was bootstrapped with [create-react-library](https://github.com/transitive-bullshit/create-react-library).

Support my OSS work by <a href="https://twitter.com/transitive_bs">following me on twitter <img src="https://storage.googleapis.com/saasify-assets/twitter-logo.svg" alt="twitter" height="24px" align="center"></a>
