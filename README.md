## Hi there, I'm Muhammad Waqas 👋
```php
<?php

namespace MuhammadWaqas;

class About extends Me
{
  public function getBio(): string
  {
    return 'I am Muhammad Waqas, a web developer with over 8 years of experience and a passion for crafting exceptional digital solutions. I've successfully completed over 100+ projects, specializing in Laravel, Vue.js, and API development. My expertise extends to building efficient UIs with Filament and resolving bugs swiftly. 
  
    Let's create your dream digital solution together! Here is what I bring to the table:
  
    Laravel Development: Build robust and scalable web applications with Laravel, ensuring smooth performance and user experiences.
    Interactive UIs with Vue.js or React.js: I leverage Vue.js or React.js to create user-friendly interfaces and engaging single-page applications. 
    Filament Expert: I specialize in customizing Filament for efficient management of your web applications.
    Seamless API Development: Design and implement RESTful APIs to facilitate communication between your web applications and other services.
    Full-Stack Development: From initial concept to deployment, I deliver tailored web solutions that are functional, user-friendly, and visually appealing.
    Bug-Free Solutions: With a keen eye for detail, I identify and resolve bugs efficiently, ensuring your applications run smoothly.
  
    Ready to elevate your online presence? Let's collaborate to bring your vision to life. Reach out today to discuss your project and take the first step towards success!';
  }

  public function getMore(): array
  {
    return [
      'work' => [
        'CTO - CentoSquare (Sept 2021 - Present)',
        'Full Stack Developer - CentoSquare (Sept 2018 - Aug 2021)',
        'Lead Developer - CentoSquare (June 2017 - August 2018)',
        'Junior Web Developer - CentoSquare (April 2016 - May 2017)',
      ],
    ];
  }

  public function getCurrentState(): array
  {
    return [
      'working_on' => [
        'Laravel, Livewire, Filament, Vue.js, and React.js',
      ],
      'learning' => [
        'Advanced Programming Techniques',
        'Goo Lang',
      ],
    ];
  }

  public function getFutureGoal(): string
  {
    return 'To contribute to open source.';
  }
}
