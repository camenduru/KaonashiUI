HOW TO RUN:

if you have a NVIDIA gpu:

run_nvidia_gpu.bat



To run it in slow CPU mode:

run_cpu.bat



IF YOU GET A RED ERROR IN THE UI MAKE SURE YOU HAVE A MODEL/CHECKPOINT IN: kaonashiUI\models\checkpoints

You can download the stable diffusion 1.5 one from: https://huggingface.co/runwayml/stable-diffusion-v1-5/blob/main/v1-5-pruned-emaonly.ckpt


RECOMMENDED WAY TO UPDATE:
To update the kaonashiUI code: update\update_kaonashiui.bat



To update kaonashiUI with the python dependencies, note that you should ONLY run this if you have issues with python dependencies.
update\update_kaonashiui_and_python_dependencies.bat


TO SHARE MODELS BETWEEN kaonashiUI AND ANOTHER UI:
In the kaonashiUI directory you will find a file: extra_model_paths.yaml.example
Rename this file to: extra_model_paths.yaml and edit it with your favorite text editor.
