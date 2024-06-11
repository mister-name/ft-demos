## What is this?

After installing ft-demos on your machine, you can start it on boot by creating an init.d script.

An example for that script lives under `init.d/flaschen-taschen-demos`.

## Installation
1. Copy the script: `cp init.d/flaschen-taschen-demos /etc/init.d/`
2. Make it executable: `chmod +x /etc/init.d/flaschen-taschen-demos`
3. Add it to the boot sequence: `update-rc.d flaschen-taschen-demos defaults`

## Usage - like any other service
1. Start the service: `service flaschen-taschen-demos start`
2. Stop the service: `service flaschen-taschen-demos stop`
3. Restart the service: `service flaschen-taschen-demos restart`

## What about the flaschen-taschen server?

The flaschen-taschen server lives under its own repo, https://github.com/hzeller/flaschen-taschen

There you will find instructions for running the server, including an init.d script for starting the server on boot.

The two init.d scripts will result in flaschen-taschen starting up and displaying as expected.
