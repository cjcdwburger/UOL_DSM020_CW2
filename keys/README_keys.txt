This directory, keys, should contain 2 .yml files, spotify_keys.yml and genius_key.yml, as shown below:

root/
├── CW2.ipynb
├── README.txt
├── input_data/
│   ├── dataset.csv
│   └── Spotify_Youtube.csv
└── keys/
    ├── spotify_keys.yml
    └── genius_key.yml

These .yml files hold the authorisation keys to use the spotify API and genius API respectively. These files
contents are as follows:

- spotify_keys.yml contains 2 fields:
    id: <your spotify app id here>
    secret: <your spotify app secret here>

- genius_key.yml contains 1 field:
    key: <your genius app key here>
