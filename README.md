# UpdateTrack

Update Track is a Python library for that implements the basics of an application with auto-update capabilities and usage tracking through a Google sheet.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install Update Track.

```bash
pip install updatetrack
```

## Usage

```python
import updatetrack

updatetrack.autoupdate() # installs latest version
updatetrack.track('this') # adds this to Google Sheet
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)