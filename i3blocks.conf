# i3blocks config file
#
# Please see man i3blocks for a complete reference!
# The man page is also hosted at http://vivien.github.io/i3blocks
#
# List of valid properties:
#
# align
# color
# command
# full_text
# instance
# interval
# label
# min_width
# name
# separator
# separator_block_width
# short_text
# signal
# urgent

# Global properties
#
# The top properties below are applied to every block, but can be overridden.
# Each block command defaults to the script name to avoid boilerplate.
command=/usr/lib/i3blocks/$BLOCK_NAME
separator_block_width=15
markup=none

# Volume indicator
#
# The first parameter sets the step (and units to display)
# The second parameter overrides the mixer selection
# See the script for details.
#[volume]
#label=VOL
#label=♪
#instance=Master
#instance=PCM
#interval=once
#signal=10

# Volumen
#[audio]
#label=
#interval=once
#command=~/.config/i3/scripts/audio.sh

#[mail]
#command=echo -e " $(sh ~/.config/i3/gmail.sh)"
#interval=1
#color=#7F00FF 

#[microphone]
#label=
#interval=5
#command=~/.config/i3/scripts/microphone.sh

# Weather
[Weather]
command=~/.config/i3/scripts/weather3.sh "san-miguel-de-tucuman"
interval=1800
#color=#c9c9ff

# Memory usage
#
# The type defaults to "mem" if the instance is not specified.
[memory]
label=
separator=false
interval=1
command=/usr/lib/i3blocks/memory
color=#dfe3ee

[memory]
label=
instance=swap
separator=true
interval=30
color=#7ea1a5

# Disk usage
#
# The directory defaults to $HOME if the instance is not specified.
# The script may be called with a optional argument to set the alert
# (defaults to 10 for 10%).
[disk]
label=
#instance=/mnt/data
interval=30
separator=false
color=#d9534f

[disk]
label=
instance=/mnt
interval=30
separator=true
color=#f0d817

# CPU usage
#
# The script may be called with -w and -c switches to specify thresholds,
# see the script for details.
#[cpu_usage]
#label=
#interval=1
#min_width=CPU:100.00%
#separator=true

[load_average]
label=
interval=5
color=#00ff7f

# Network interface monitoring
#
# If the instance is not specified, use the interface used for default route.
# The address can be forced to IPv4 or IPv6 with -4 or -6 switches.
[iface]
label=
instance=wlp4s0
color=#00FFFF
interval=10
separator=true
color=#66cd00

[bandwidth]
label=
instance=wlp4s0
interval=1
color=#83d0c9

# Battery indicator
#
# The battery instance defaults to 0.
[battery]
#label=BAT
#label=⚡
label=
#instance=1
interval=30

# Date Time
#
[time]
command= date '+%d/%m/%Y %H:%M'
label=
interval=1

# Generic media player support
#
# This displays "ARTIST - SONG" if a music is playing.
# Supported players are: spotify, vlc, audacious, xmms2, mplayer, and others.
#[mediaplayer]
#instance=spotify
#interval=5
#signal=10

# OpenVPN support
#
# Support multiple VPN, with colors.
#[openvpn]
#interval=20

# Temperature
#
# Support multiple chips, though lm-sensors.
# The script may be called with -w and -c switches to specify thresholds,
# see the script for details.
#[temperature]
#label=TEMP
#interval=10

# Key indicators
#
# Add the following bindings to i3 config file:
#
# bindsym --release Caps_Lock exec pkill -SIGRTMIN+11 i3blocks
# bindsym --release Num_Lock  exec pkill -SIGRTMIN+11 i3blocks
#[keyindicator]
#instance=CAPS
#interval=once
#signal=11

#[keyindicator]
#instance=NUM
#interval=once
#signal=11
