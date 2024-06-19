# PROJECT MOVED TO PlanQK organization

**NOTICE:** This project has moved to the GitHub PlanQK organization for continued updates and development. You can find the latest version of this project at (https://github.com/PlanQK/planqk-demo-starter-gradio).

# A PlanQK Demo Example using Gradio

This is an example of a PlanQK Demo created with [Gradio](https://www.gradio.app).
The demo creates a web user interface to demonstrate the [Quantum Random Number Generator](https://platform.planqk.de/marketplace/apis/88b46e18-3d5f-4674-ba04-0d3416c0decd) published on the PlanQK Marketplace.

## Try it out

To run the demo subscribe to the [Quantum Random Number Generator](https://platform.planqk.de/marketplace/apis/88b46e18-3d5f-4674-ba04-0d3416c0decd) with an Application.
Then add the credentials of your Application as environment variables.

Run it locally with:

```bash 
conda env create -f environment.yml
conda activate demo-starter-gradio
gradio app.py
```
