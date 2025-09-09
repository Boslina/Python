🌍 Ubuntu-Inspired Image Fetcher

"I am because we are" – The Wisdom of Ubuntu

This project is a simple yet thoughtful Python script that allows users to fetch images from the web and save them locally in an organized folder. Inspired by the Ubuntu philosophy of community and sharing, this tool emphasizes respectful and mindful interaction with online resources.

✨ Features

📥 Fetches images from any valid image URL.

📂 Saves downloaded images into a dedicated Fetched_Images folder.

🔄 Automatically prevents duplicate filenames by appending counters.

⚡ Handles connection errors gracefully with clear messages.

🛡️ Validates and assigns a default filename when missing.

🛠️ Requirements

Make sure you have the following installed on your system:

Python 3.7+

Required Python libraries:

requests

Install dependencies with:

pip install requests

▶️ Usage

Clone or download this repository.

Open a terminal in the project folder.

Run the script:

python ubuntu_image_fetcher.py


Enter a valid image URL when prompted, for example:

Please enter the image URL: https://example.com/sample.jpg


The image will be saved in the Fetched_Images folder.

📂 Output Example

If you download multiple images with the same name, the script avoids overwriting:

Fetched_Images/
│── sample.jpg
│── sample_1.jpg
│── sample_2.jpg

⚠️ Error Handling

If the URL is invalid or unreachable → A clear connection error message is displayed.

If the image lacks a filename → The script saves it as downloaded_image.jpg.

If permission or filesystem issues occur → You’ll see a descriptive error message.

🌱 Philosophy

This project is inspired by Ubuntu, a philosophy that values community, sharing, and connection. Every image fetched is a reminder that we are part of a greater digital community.
