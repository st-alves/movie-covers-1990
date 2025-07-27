# Movie Covers (1991-2000)
Movie covers from the 1990's (1991-2000).

## ID
Use the IMDb movie ID without the initial "tt". For greater compability in future, remove left zeros (0107048 -> 107048).

## How to use links
Use this URL pattern for default covers (you'll have to implement the automation yourself):
```python
    https://raw.githubusercontent.com/st-alves/movie-covers-${decade}/refs/heads/main/${type}/${movie_id}.jpg"
```

Example: 
<br>```https://raw.githubusercontent.com/st-alves/movie-covers-1990/refs/heads/main/default/107048.jpg```

Only "letterboxd" is available for ```${type}``` for now.

### Main Project
[Movie Covers](https://github.com/st-alves/movie-covers)
