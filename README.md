# PosterPy

This is a python script that helps you to search, download movie posters and set them as folder icons. PosterPy uses the popular [IMDbPY](https://imdbpy.github.io/) package to search movies and [TMDb a.k.a The Movie Data Base](https://www.themoviedb.org/) API to download movie posters.

![iaa1](https://user-images.githubusercontent.com/55880211/80022395-a2b95700-84f9-11ea-8dca-d0f0eff217bd.gif)

## For Your Attention 

- Your PC may take some time to index the newly added icons. If the icons doesn't appear after 3 - 5 minutes try clearing and resetting thumbnail cache of our PC. [Here](https://www.sevenforums.com/tutorials/10797-thumbnail-cache-clear-reset.html) is a article on how to clear and reset thumbnail cache in Windows.

- Since PosterPy is using the TMDb API to download movie posters you need to have a TMDb API key in order to use this script. To register for an API key click [here](https://www.themoviedb.org/account/signup). Once you register an account [this](https://developers.themoviedb.org/3/getting-started/introduction) will help you to request and find your API key. (This is an one time process. Once you obatin your API key you need to enter it to the script when it ask for the key and that's it.)

## I don't like these icons. How do i remove them?

To remove the poster icon from a folder, just delete the .ico and desktop.ini file from the folder. desktop.ini file is hidden by default. Therefore make sure you have __Show Hidden Items__ option ticked. 

## Screenshot

![Untitled collage](https://user-images.githubusercontent.com/55880211/80029365-4f98d180-8504-11ea-84e3-f94a1fe64e09.png)

## Git Installation
```
# clone the repo
$ git clone https://github.com/sameera-madushan/PosterPy.git

# change the working directory to PosterPy
$ cd PosterPy

# install the requirements
$ pip3 install -r requirements.txt
```

## Usage

```
python posterpy.py
```

## Support & Contributions
- Please ⭐️ this repository if this project helped you!
- Contributions of any kind welcome!

## License
PosterPy is made with ♥ by [@_\_sa_miya__](https://twitter.com/__sa_miya__) and it is released under the MIT license.

## Contributors

Thanks goes to this wonderful person. :heart:

<table>
  <tr>
    <td align="center"><a href="https://github.com/sdushantha"><img src="https://avatars1.githubusercontent.com/u/27065646?s=400&u=d50283901a14e11d6d387b7af1019bdaf12d3f93&v=4" width="100px;" alt=""/><br /><sub><b>Siddharth Dushantha</b></sub></a></td>

</table>

## Attribution

<p align="center">
  <img src="https://user-images.githubusercontent.com/55880211/80030773-4a3c8680-8506-11ea-876c-31501affbf0c.jpg">
  Movie posters are powered by themoviedb.org
</p>
