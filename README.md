# Installation Guide

## Complete Installation Guide
1. Download the software from the repository.
2. Follow the instructions to install dependencies.
3. Run the installation script.

## Cron Jobs
- To set up cron jobs, edit your crontab file using `crontab -e`.
- Add the following lines for scheduled tasks:
  - `0 * * * * /path/to/script`  # Runs every hour.

## Fan Control
- Ensure the fan control script is executable.
- Use the command `./fan_control` to start managing fan speeds based on temperature.

## Troubleshooting
- If you encounter issues, check the log files in the `logs/` directory. 
- Common error messages can be found in the documentation.

## ASUS Router Configuration
1. Access the router settings at `192.168.1.1`.
2. Navigate to the "Advanced" section.
3. Set up port forwarding according to the application's requirements.

For more detailed instructions, refer to the official documentation or support.