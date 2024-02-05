# Face Recognition Attendance System

## Overview
The Face Recognition Attendance System is a comprehensive solution designed for automated attendance tracking in educational settings. Utilizing advanced deep learning algorithms, including Siamese networks, this system offers real-time recognition of individuals, enabling efficient and accurate attendance management. Key features include a real-time dashboard for monitoring attendance status, voice-activated camera activation, automatic database entry for unrecognized individuals with admin approval, and seamless integration with Raspberry Pi for enhanced portability and computational capabilities.

## Features
- **Facial Recognition:** Automated attendance tracking through facial recognition technology, utilizing Siamese networks for accurate similarity learning.
- **Real-Time Dashboard:** Web-based dashboard for monitoring attendance status, generating reports, and managing system settings.
- **Automatic Database Entry:** Unrecognized individuals captured on video are added to the database with admin approval, ensuring comprehensive attendance records.

## Installation
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Prathamesh-Bhaskar/Facial-Attendace-System
# Install Dependencies:
   ```bash
pip install -r requirements.txt
# Usage
```markdown
## Usage
1. **Run the Main Script:**
   ```bash
   python main.py

## Configuration
- Modify the `config.py` file to adjust settings such as database connection details, camera settings, and voice recognition parameters.
## Access the Real-Time Dashboard:
Open your web browser and navigate to http://localhost:8000
## Technical Details
- **Siamese Networks:** Utilized for accurate facial recognition by learning embeddings that map input images to latent representations, enabling similarity comparison.
- **User Interface (UI):** Developed using HTML, CSS, and JavaScript, with Flask as the backend framework, to create an intuitive and user-friendly real-time dashboard.
- **Voice Activation:** Implemented using speech recognition libraries and integrated with the camera activation functionality for hands-free operation.
- **Database Management:** Utilized SQLite database for storing attendance records and managing user data.

## Contributing
Contributions are welcome! If you have any ideas, enhancements, or bug fixes, please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


