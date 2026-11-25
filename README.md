# Solar Observations

This repository contains a collection of Python Jupyter notebooks designed for learners who are novices in solar physics. Through hands-on data retrieval and visualization, these notebooks guide users in exploring the features and dynamics of the Sun using imagery and data from two landmark missions:
* **[Solar Dynamics Observatory (SDO)](https://sdo.gsfc.nasa.gov/):** High-resolution observations available from 2010 to the present.
* **[Solar and Heliospheric Observatory (SOHO)](https://soho.nascom.nasa.gov/):** Observations available from the late 1990s to the present.

Together, these two missions provide continuous, high-cadence solar observations spanning more than three solar cycles.

## Repository Contents & Recommended Workflow

The notebooks are designed to be explored in sequence, moving from event identification to multi-layer solar imaging:

1. **`GOES_XRay.ipynb`** — Introduces GOES X-ray flux plots so learners can identify the timing of solar flares and select target events to investigate in the imagery notebooks.
2. **`Whitelight_magnetogram.ipynb`** — Demonstrates how to access SDO white-light and magnetogram imagery of the photosphere to explore the relationship between sunspots, magnetic active regions, and EUV emission.
3. **`Solar-Imagery_EUV.ipynb`** — Guides users in accessing SDO Extreme Ultraviolet (EUV) imagery to examine the structure and dynamics of UV and X-ray active regions in the solar atmosphere.
4. **`Solar-Imagery_SOHO_Coronagraph.ipynb`** — Covers accessing white-light coronagraph imagery (SOHO/LASCO), allowing learners to connect outer coronal structures (such as streamers and CMEs) to inner coronal features seen in EUV.
5. **`SOHO-Imagery_Answers.ipynb`** — Provides worked examples using white-light and EUV imagery from SOHO, enabling learners to explore these same solar properties during the pre-SDO era (late 1990s through 2010). The detailed explanations and guided questions are left out of this notebook but learners can view the SDO notebook and follow those instructions while using the SOHO data. 

> **Instructor & Self-Study Note:** Each of the first four notebooks has a corresponding `_Answers.ipynb` file containing completed code and sample outputs that learners can use to check their work.

## How to Use These Notebooks

* **Environment:** All notebooks are standalone and were developed to run directly in **Google Colab**, though they can easily be adapted for local Jupyter Notebook, JupyterLab, or HelioCloud environments.
* **Dependencies:** Each notebook includes setup cells at the top to install required heliophysics and astronomy packages (such as `sunpy`, `astropy`, `aiapy`, and `solarmach`) and create a local `./data` directory for downloaded FITS files.
