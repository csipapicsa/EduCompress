# EduCompress: The Ultimate Presentation Video Compressor

Welcome to [EduCompress](EduCompress-V1.1.1.exe), the efficient and user-friendly application designed specifically for educators, students, and professionals. The drag & drop interface simplifies the process of compressing presentation videos without sacrificing quality reaching 20-30 times more space saving than the original video.

## ✅ Key Features:

- **🗜️ Superb Compression**: Shrink your lecture and presentation videos to 20-30 times smaller sizes with our advanced algorithm that maintains clarity at 5 frames per second, optimizing for slide-based content.

- **🙂Drag & Drop Simplicity**: No complex settings to navigate. Just drag your video onto the app, and EduCompress takes care of the rest.

- **📊 🎓Tailored for Education**: Whether it's for online learning, archiving, or distribution, make your large lecture files manageable and easily accessible.

- **Space Saver**: Save valuable disk space and bandwidth, making it perfect for sharing over email or cloud services.

- **Quality Retention**: Our compression technique is fine-tuned to preserve the quality of your slides and lecture content.

EduCompress is your go-to tool for making presentation sharing as seamless as possible. Give it a try and see just how easy video compression can be!

## ❓How to Use

- Simply drag and drop your video file onto the app. The conversion starts immediately, saving the compressed video file in the same folder with the original name followed by an additional suffix to denote compression.

- Your system will detect as a safety thread. Since code signiging costs between 200 - 500 USD / year, I have not included the signature in the app.

### ⚠️ Important Notice Regarding Security Warnings

When you download and run EduCompress, your operating system may flag it as a potential security threat. This is a standard warning for unsigned applications. Code signing certificates, which help to verify the authenticity of the software, typically cost between $200 - $500 per year. To keep EduCompress accessible and free, it is currently distributed without such a signature.

#### What This Means for You
- This warning does not indicate that EduCompress is harmful to your system.
- It simply means that the application is not signed by a recognized Certificate Authority.
- I assure you that EduCompress is developed with the utmost care for security and functionality.

#### Bypassing the Warning 
- On Windows, you can choose to run the application anyway by clicking "More info" and then "Run anyway."
- On macOS, you can open the application by right-clicking (or control-clicking) the app icon and selecting "Open."

Your understanding and trust are appreciated, and I'm committed to maintaining the integrity and safety of EduCompress.

Note: If you intend to convert standard videos, such as those containing music, dynamic scenes, or people, the resulting video quality may be terrible. This is because EduCompress's algorithm is specifically optimized for presentation-style content, not for general video compression. As such, it may not effectively handle the complexities of regular videos with continuous motion and sound.

### Example videos

I recorded my [VS code screen](example_videos/vs-code-example-original.mp4) for 23 seconds with an internal recorder, generating a 23.4 MB video. Most commonly used screen recorders will generate videos with a similar size, averaging ~ 1 MB per second, which is quite substantial.

However, with EduCompress, the video can be compressed down to just 443 KB, resulting in a video that is ~50 times smaller in size. You can check out the compressed version [here](example_videos/vs-code-example-compressed.mp4).

## Technical Details

- EduCompress leverages the powerful `ffmpeg` for video processing, a leading multimedia framework capable of encoding, decoding, transcoding, muxing, demuxing, streaming, filtering, and playing almost any type of media. Discover more about `ffmpeg` [here](https://www.ffmpeg.org/).
- The output video is processed to have 5 FPS (frames per second) and the audio is encoded to MP3 format with a bitrate of 128 kbps, a sample rate of 44100 Hz, and a single (mono) audio channel. Video compression is achieved using the `libx264` codec, renowned for its efficiency and quality.

### Compatibility

EduCompress is designed to work with Windows 64-bit systems. Compatibility with other operating systems or versions is not currently available but may be considered for future updates.

#### Supported Operating Systems:
- Windows 64-bit

#### Not Currently Supported:
- Windows 32-bit
- macOS
- Linux

## Additional Information

If you are interested in seeing EduCompress on one of the unsupported platforms, or if you're experiencing issues on a supported system, please let us know. Your feedback is valuable and can help prioritize development efforts. You can reach out for inquiries, support, or to express your interest in a specific version by emailing: `gergo gyori gmail`.

For developers or enthusiastic users who would like to contribute to expanding the compatibility of EduCompress, we welcome pull requests and community contributions on our GitHub repository.

Your support and contributions make a significant difference in the growth and improvement of EduCompress. If you find this tool helpful and would like to support its development, consider [buying me a coffee](https://www.buymeacoffee.com/savpank). Every coffee fuels more hours of open-source development!
