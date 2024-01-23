# streamlit-camera-input-live

[![PyPI version](https://img.shields.io/pypi/v/streamlit-camera-input-live.svg?logo=pypi&logoColor=FFE873)](https://pypi.org/project/streamlit-camera-input-live/)
[![PyPI downloads](https://img.shields.io/pypi/dm/streamlit-camera-input-live.svg)](https://pypistats.org/packages/streamlit-camera-input-live)
[![GitHub](https://img.shields.io/github/license/blackary/streamlit-camera-input-live.svg)](LICENSE)
[![Code style: Black](https://img.shields.io/badge/code%20style-Black-000000.svg)](https://github.com/psf/black)

Alternative version of st.camera_input which returns the webcam images live, without any button press needed

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://camera.streamlitapp.com)

## Installation instructions

```sh
pip install streamlit-camera-input-live
```

## Usage instructions

```python
import streamlit as st

from camera_input_live import camera_input_live

image = camera_input_live()

if image:
  st.image(image)
```
