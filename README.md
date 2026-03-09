# Pettersson Sikkerhet

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/2mebp/pettersson-sikkerhet.git
   cd pettersson-sikkerhet
   ```
2. Install the required dependencies:
   ```bash
   sudo apt install <required-packages>
   ```

## Verification
After installation, verify the setup by running:
```bash
./verify_setup.sh
```
This script checks the environment and ensures everything is configured correctly.

## Cron Jobs Schedule
Set up cron jobs to automate tasks. Open the crontab editor:
```bash
crontab -e
```
Then add your desired job:
```bash
# Run script every hour
0 * * * * /path/to/your/script.sh
```

## Fan Control
To control the fan speed based on temperature, ensure you have configured the relevant settings in your configuration file, e.g. `fan_control.conf`. Refer to the documentation for the parameters available.

## ASUS Router Configuration
For ASUS router configuration, log into the router's web interface and navigate to the appropriate sections:
- Set up your network settings.
- Configure port forwarding if necessary.

Consult the ASUS documentation for detailed instructions related to your specific model.

## Troubleshooting
If you encounter issues:
- **Check the logs**: Review the logs located in `/var/log/pettersson-sikkerhet/`
- **Verify configurations**: Ensure all configurations are set correctly.
- **Reboot components**: Sometimes, a reboot may resolve connectivity or service issues.
- If all else fails, check [GitHub issues](https://github.com/2mebp/pettersson-sikkerhet/issues) for similar problems and solutions.