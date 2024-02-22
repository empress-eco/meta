![Meta Logo](https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png

# Meta: Power-Up Your Framework

Welcome to Meta, the robust integration tool that supercharges your Framework with the capabilities of Meta's Cloud API. Seamlessly send a variety of WhatsApp messages, including text, media, and template-based messages, and automate welcome messages for new users. 

Explore the [documentation](https://empress.eco/) to learn more about Meta. For bug reporting or feature requests, please visit [this page](https://github.com/empress-eco/meta/issues).

## About Meta Integration

Meta is designed to take your Framework to the next level by integrating it with Meta's Cloud API. It's an essential tool for businesses seeking to enhance their communication capabilities via WhatsApp.

### Key Features:
- Supports Empress Version 14.
- Enables Text, Media, and Template-Based WhatsApp Messaging.
- Sends automated Welcome Messages to new users.

## Technical Stack and Setup Instructions

Meta relies on the Framework and Meta's Cloud API. 

### Prerequisites
- Meta for Developers Account
- WhatsApp configured in the Meta Developer Account
- Verified Business on Meta
- Verified WhatsApp Number and a Permanent Token

### Installation
To get Meta up and running, follow these steps:

1. Clone the repository: 
    ```sh
    git clone https://github.com/empress-eco/meta.git
    ```

2. Install the application: 
    ```sh
    bench get-app https://github.com/efeone/Empress_meta_integration.git
    bench setup requirements
    bench build --app Empress_meta_integration
    bench --site [your.site.name] install-app Empress_meta_integration
    bench --site [your.site.name] migrate
    ```

## Usage
Meta simplifies your WhatsApp communication process on the Framework. It supports three primary message types - text, document, and template, catering to a broad range of messaging needs. Check out the [documentation](https://empress.eco/) for a quick start guide and practical usage tips.

## Contribution Guidelines
We welcome your contributions! Here's how you can contribute:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

For further guidelines, you can refer to the [Empress Contribution Guidelines](https://github.com/Empress/Empress/wiki/Contribution-Guidelines).

## License and Acknowledgements

This project is licensed under the MIT License.

We extend our heartfelt thanks to the Empress Community for their foundational contributions to this project. Their innovation and commitment have been instrumental in shaping the functionalities we rely on. We are profoundly grateful for their pioneering work and ongoing support.