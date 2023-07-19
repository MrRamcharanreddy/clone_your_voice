# LipSync with Wav2Lip

This Colab notebook demonstrates how to perform LipSync on a video using Wav2Lip. The goal is to make anyone speak anything by synchronizing the audio with a video.

The notebook is divided into several steps:

## Step 1: Setup Wav2Lip

This step installs the necessary dependencies and downloads the pre-trained model for Wav2Lip.

## Step 2: Select a Youtube Video

In this step, you can specify a Youtube video URL, and the notebook will download and trim the video to a specified interval.

## Step 3: Select Audio

This step allows you to record your own audio, upload an audio file from your local drive, or use a custom audio file from your Google Drive.

## Step 4: Start Crunching and Preview Output

The final step runs the LipSync process, combining the selected video and audio to generate a LipSynced output. It also previews the final video.

Please note the following:
- Do not upload videos longer than 60 seconds.
- The trimmed video must have a face on all frames for accurate LipSync.

For more information on the Wav2Lip project, you can refer to the [Github repository](https://github.com/Rudrabha/Wav2Lip) and the [original Colab notebook](https://colab.research.google.com/drive/1tZpDWXz49W6wDcTprANRGLo2D_EbD5J8?usp=sharing).

The notebook has been modified by [justinjohn-03](https://github.com/justinjohn0306).

## Acknowledgements

- [Wav2Lip](https://github.com/Rudrabha/Wav2Lip) - Lip-syncing videos in the wild.
- [yt-dlp](https://github.com/yt-dlp/yt-dlp) - A youtube-dl fork with additional features.

Please follow the instructions provided in each step of the notebook to execute the LipSync process successfully. Enjoy LipSyncing with Wav2Lip!
