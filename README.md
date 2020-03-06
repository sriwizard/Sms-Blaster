# sms-blaster
## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/installing/) to install Sms-Bomber.

```bash
git clone https://github.com/sriwizard/sms-blaster.git
cd sms-blaster
pip3 install -r requirements.txt
```

## Usage

```bash
python3 bomber.py <TARGET>
```

where TARGET is target mobile number.

## Options

```
usage: bomber.py [-h] [--sms SMS] [--threads THREADS] TARGET

positional arguments:
  TARGET                    Target mobile number without country code (default:+91)

optional arguments:
  -h, --help                show this help message and exit
  --sms SMS, -S SMS         Number of sms to target (default: 5000)
  --country COUNTRY, -c COUNTRY
                        Country code without (+) sign (default: 91)
  --threads THREADS, -T THREADS
                            Number of threads (default: 25)
  --proxy, -p           Use proxy for bombing (It is advisable to use this
                          option if you are bombing more than 5000 sms)
  --verbose, -v         Verbose
  --verify, -V          To verify all providers are working or not
```

## License

This project is licensed under the [GNU General Public License v3.0](https://github.com/sriwizard/sms-blaster/blob/master/LICENSE)
