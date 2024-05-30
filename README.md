# ProjetDataSciences

<p>Our goal is to develop a model that can accurately identify the genre of a piece of music. This involves training the model using a diverse dataset of musical tracks from various genres, allowing it to learn the unique features and characteristics associated with each genre.</p>
<p>We are going to try different models and compare their performance to determine which one is the most effective at classifying music genres.</p>

## Dataset Informations

### Number of Instances

50,000

### Number of Attributes

17 Input Features + 1 Target('Music Genre')

## Attribute Information

### instance_id

A unique identifier for each instance in the dataset, represented as a floating-point number. There are `50,000` instances in total.

### artist_name

The name of the artist who created the track, represented as a string (object).

### track_name

The name of the track, represented as a string (object).

### popularity

A measure of the popularity of the track, represented as a floating-point number between `0` and `100`. Higher values indicate greater popularity.

### acousticness

A measure of the acousticness of the track, represented as a floating-point number between `0` and `1`. Higher values indicate greater acousticness.

### danceability

A measure of the danceability of the track, represented as a floating-point number between `0` and `1`. Higher values indicate greater danceability.

### duration_ms

The duration of the track in milliseconds, represented as a floating-point number.

### energy

A measure of the energy of the track, represented as a floating-point number between `0` and `1`. Higher values indicate greater energy.

### instrumentalness

A measure of the instrumentalness of the track, represented as a floating-point number between `0` and `1`. Higher values indicate greater instrumentalness.

### key

The key in which the track is performed, represented as a string (object). There are <b>12</b> possible values: `C`, `C#`, `D`, `D#`, `E`, `F`, `F#`, `G`, `G#`, `A`, `A#`, and `B`.

### liveness

A measure of the liveness of the track, represented as a floating-point number between `0` and `1`. Higher values indicate greater liveness.

### loudness

A measure of the loudness of the track, represented as a floating-point number in `decibels (dB)`. Higher values indicate greater loudness.

### mode

The mode in which the track is performed, represented as a string (object). There are two possible values: `major` and `minor`.

### speechiness

A measure of the speechiness of the track, represented as a floating-point number between 0 and 1. Higher values indicate greater speechiness.

### tempo

The tempo of the track in `beats per minute (BPM)`, represented as a string (object).

### obtained_date

The date on which the track information was obtained, represented as a string (object).

### valence

A measure of the valence (positivity) of the track, represented as a floating-point number between `0` and `1`. Higher values indicate greater positivity.

### music_genre

The genre of the track, represented as a string (object). There are multiple possible genres in the dataset.

## Usage

Create a virtual environment:

```bash
python3 -m venv .venv
```

and activate it:

```bash
source .venv/bin/activate
```

or:

```bash
source .venv/Scripts/activate
```

Install the dependencies when the .venv is activated:

```bash
pip install -r requirements.txt
```

and to deactivate it when you're done:

```bash
deactivate
```
