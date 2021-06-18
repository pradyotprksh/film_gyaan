## IN DEVELOPMENT

# [film_gyaan](https://pub.dev/packages/film_gyaan)

An unofficial dart SDK which will connect to https://api.themoviedb.org/ for you.

For details on API go to https://developers.themoviedb.org/3/getting-started/introduction.

This is an unofficial package for TheMovieDB. And I don't take any credit for the APIs related
to TheMovieDB.

1. Create an API Key at https://developers.themoviedb.org/ and use this in the package while initializing.

3. Add `film_gyaan: <version>` to the project.

4. Add `import 'package:film_gyaan/film_gyaan.dart';` to start accessing the SDK features.

5. Initialize the FilmGyaan with the API key.

```
    var filmGyaan = FilmGyaan(
        credentials: Credentials(
            apiKey: '<API_KEY>',
        ),
    );
```

6. Start using the package to get movie list, details and many more.

The project is under development and will try to add the other APIs provided by TheMovieDB.
Will make the repository public when the development is done for raising the issues and feature requests.
