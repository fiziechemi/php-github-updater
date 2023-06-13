# GitHub Release Updater
This is a PHP class that allows you to update your project from the GitHub repository releases. It is a simple and efficient way to keep your project up-to-date with the latest releases.

## Preparation
Before using this class, you need to generate a personal access token on GitHub. Follow these steps:

- Go to https://github.com/settings/tokens/new
- Select the repository and enable read-only access for Contents and Metadata.
- Click on "Generate token" and copy the token.

## Usage

To use this class, follow these steps:

- Include the update.php file in your project.
- Initialize the GitUpdate class to start the update process. Use the following parameters:
```
Copy codenew GitUpdate($username, $repository, $token, $version, $admin, $mailer)
```

### $username: Your GitHub username.
### $repository: The name of your GitHub repository.
### $token: The personal access token you generated earlier.
### $version: The current version number of your project.
### $admin: The email address of the admin who will receive an email in case of update failure.
### $mailer: The email address that the email will be sent from.

If a new release is available, the class will update your project automatically.

## Conclusion
This class is a simple and efficient way to keep your project up-to-date with the latest releases on GitHub. It is easy to use and can save you a lot of time and effort. If you have any questions or issues, please feel free to contact us.