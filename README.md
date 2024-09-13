**🎵Terraform Spotify Playlist Automation🎵**

Automate the creation and management of your Spotify playlists for different occasions using Terraform! Whether it's a serene morning, a relaxing evening, or an electrifying party night, this project will help you manage your playlists effortlessly.

**🚀 Project Overview**

This project leverages Terraform to automate the creation of multiple Spotify playlists tailored for various occasions. By defining the playlists as Terraform resources, you can easily manage and update them with a single command. No more manual playlist creation—let Terraform handle the heavy lifting!

**🛠 Prerequisites**

Before you dive in, make sure you have the following set up:

1. **Terraform Installed**: [Install Terraform](https://www.terraform.io/downloads.html) on your machine.
2. **Docker Installed**: Ensure Docker is installed and running on your system. [Get Docker](https://docs.docker.com/get-docker/).
3. **Spotify Account**: A Spotify account is required (no need for premium access).
4. **Spotify Developer Account**: Register at [Spotify for Developers](https://developer.spotify.com/dashboard/applications) and create an application to obtain your Client ID and Client Secret.
5. **Spotify Provider for Terraform**: Install and configure the [Spotify Provider for Terraform](https://registry.terraform.io/providers/conradludgate/spotify/latest).
6. **VS Code Editor**: Recommended for editing and managing Terraform files. [Download VS Code](https://code.visualstudio.com/).

**📋 Steps to Complete the Project**

Follow these steps to automate your Spotify playlists:

**1. **Creating Terraform Code****
   - Start by defining your Terraform configuration files. Specify the provider, and set up the resources for your playlists.

**2. **Define Provider****
   - Use the Spotify provider in Terraform to interact with your Spotify account.

**3. **Need API Key****
   - Obtain the API key by authenticating with your Spotify Developer account.

**4. **Start with App Creation****
   - Create a new application on the Spotify Developer Dashboard. This will give you the necessary Client ID and Client Secret.

**5. **Enter Details****
   - Input your Spotify application's Client ID and Secret in your Terraform configuration.

**6. **Run the Spotify Auth App and Get the API Key****
   - Use Docker to run a Spotify Auth app that will help you generate the API key required for Terraform.

**7. **Continue Creating Terraform Code****
   - With the API key in hand, finalize your Terraform code. Define the playlists, tracks, and any other resources you need.

**8. **Initialize and Apply Terraform Configuration****
   - Initialize your Terraform workspace and apply the configuration to create your playlists.

**9. **Verify Playlists on Spotify****
   - Check your Spotify account to see the newly created playlists. Customize them further as needed!

**🎉 Project Benefits**

- **Time-Saving**: Automate the repetitive task of playlist creation.
- **Consistency**: Ensure all your playlists follow a similar structure and theme.
- **Scalability**: Easily manage and update multiple playlists across your Spotify account.

**🙌 Acknowledgments**

Special thanks to the Terraform and Spotify teams for providing the tools to make this project possible.

- Special thanks to the [Terraform](https://www.terraform.io/) and [Spotify](https://www.spotify.com/) teams for providing the tools to make this project possible.
