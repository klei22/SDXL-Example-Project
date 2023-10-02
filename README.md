## SDXL Example Project

This project provides examples of using SDXL (Stability Diffusion XL) for
text-to-image generation. The examples are implemented in a Python script called
`example_prompt.py`, which generates an output image named `output.jpg`.

## Setup

To run the examples, follow these steps:

1. Create a virtual environment using Python 3:

```sh
python3 -m venv venv
```

2. Activate the virtual environment:

```sh
source venv/bin/activate
```

3. Install the required packages using pip and the `requirements.txt` file:

```sh
pip3 install -r requirements.txt
```

## Usage

To generate an image using SDXL, run the following command:

```sh
python3 example_prompt.py
```

This will execute the `example_prompt.py` script, which will generate an output image named `output.jpg`.

Make sure to modify the `prompt` variable in the `example_prompt.py` script to specify the desired text prompt for generating the image.

## License

This project is licensed under the Apache-2.0 License - see the [LICENSE](LICENSE) file for details.
