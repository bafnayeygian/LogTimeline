# LogTimeline

Merge multiple timestamped log files into a single chronological incident timeline with source tracking and parse-error reporting.

Version: **1.0.0**

## Installation

```bash
git clone https://github.com/bafnayeygian/LogTimeline.git
cd LogTimeline
python -m pip install .
```

## Usage

```bash
log-timeline --help
```

## Development

```bash
python -m unittest discover -s tests -v
python -m compileall -q src
```

## License

MIT License.
