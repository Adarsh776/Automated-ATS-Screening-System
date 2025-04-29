# Smart ATS (Application Tracking System)

A powerful resume analysis tool that uses Google's Gemini AI to evaluate resumes against job descriptions, providing detailed feedback and matching percentages.

## Features

- PDF resume analysis
- Job description matching
- Percentage-based matching score
- Missing keywords identification
- Profile summary generation
- User-friendly web interface

## Prerequisites

- Python 3.7 or higher
- Google API key for Gemini AI
- Required Python packages (listed in requirements.txt)

## Installation

1. Clone this repository:
```bash
git clone https://github.com/Adarsh776/Automated-ATS-Screening-System
cd Automated-ATS-Screening-System
```

2. Install the required packages:
```bash
pip install -r requirements.txt
```

3. Create a `.env` file in the project root and add your Google API key:
```
GOOGLE_API_KEY=your_api_key_here
```

## Usage

1. Run the application:
```bash
streamlit run app.py
```

2. Open your web browser and navigate to the provided local URL (typically http://localhost:8501)

3. In the application:
   - Paste the job description in the text area
   - Upload your resume in PDF format
   - Click the "Submit" button to analyze

4. The system will provide:
   - Job description match percentage
   - List of missing keywords
   - Profile summary

## Technologies Used

- Streamlit - Web application framework
- Google Gemini AI - AI model for analysis
- PyPDF2 - PDF processing
- Python-dotenv - Environment variable management

## Project Structure

```
.
├── app.py              # Main application file
├── requirements.txt    # Python dependencies
├── .env               # Environment variables (create this file)
└── README.md          # Project documentation
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.


## Acknowledgments

- Google Gemini AI for providing the AI capabilities
- Streamlit for the web framework
- All contributors and users of this project 