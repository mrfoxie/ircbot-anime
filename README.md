
# IRC Anime Bot

This is an IRC bot that provides anime-related functionality. The bot connects to an IRC server, joins a specified channel, and responds to various commands related to anime. It can provide information about anime series, characters, episodes, and more.

## Prerequisites

- Python 3.x
- socket module
- requests module

## Usage

1. Clone the repository:

   ```shell
   git clone https://github.com/mrfoxie/ircbot-anime.git
   ```

2. Navigate to the project directory:

   ```shell
   cd ircbot-anime
   ```

3. Open `main.py` and modify the following variables according to your desired IRC server and channel:

   ```python
   server = "irc.libera.chat"
   port = 6667
   channel = "#anime"
   bot_name = "AnimeBot"
   ```

4. Run the bot:

   ```shell
   python main.py
   ```

5. The bot will connect to the IRC server, join the specified channel, and start listening for anime-related commands.

## Available Commands

- `!anime <title>`: Retrieves information about the specified anime series.
- `!character <name>`: Retrieves information about the specified anime character.
- `!episode <anime_title> <episode_number>`: Retrieves information about a specific episode of an anime series.
- `!randomanime`: Retrieves information about a randomly selected anime series.
- `!topanime`: Retrieves a list of top-rated anime series.
- `!schedule`: Retrieves the airing schedule of currently ongoing anime series.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b my-new-feature`
3. Make your changes and commit them: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
