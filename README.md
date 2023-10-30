# User Follow/Unfollow Feature

## Introduction
This repository demonstrates how to implement a user follow/unfollow feature in a web application using Django. The feature allows users to follow and unfollow other users, providing a seamless social interaction experience.

## How It Works
The implementation involves several key steps:
1. **Database Model**: We extend the default Django User model to include a ManyToMany relationship for followers and followees.

2. **Views and URL Patterns**: We create views to handle following and unfollowing actions and define URL patterns for these views.

3. **Templates**: We modify user profile templates to display the follow/unfollow button and the number of followers.

4. **JavaScript**: We use JavaScript to handle button toggling without the need for full page refreshes.

## Usage
To incorporate this feature into your Django project, follow the step-by-step guide provided in the [User Follow/Unfollow Documentation](docs/user_follow_unfollow.md). This guide includes detailed code snippets and explanations to help you seamlessly integrate the feature into your application.

## License
This project is open-source and available under the [MIT License](LICENSE).

## Contributing
We welcome contributions and bug reports. Feel free to fork this repository, make your changes, and submit a pull request.

## Issues
If you encounter any issues or have questions, please check the [Issues](https://github.com/your-username/your-repo/issues) section or create a new one.

Happy coding!
