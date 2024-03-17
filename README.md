# WebVTT translation script

This is an experimental script (composed with AI help) to automatically translate
a webvtt with internet translation services.

It removes extended WebVTT features to produces a plain simple webvtt to be process be MS Stream:
```
python script_name.py -in input.vtt,de -out output.vtt,en
```

TODO: Access to the translation service