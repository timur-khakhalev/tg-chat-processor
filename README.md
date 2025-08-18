# Telegram Chat Processor

Save tokens for an AI that you want to use to process your Telegram chat history **60k to ~20k tokens**

A client-side tool to process and filter Telegram chat exports (`result.json`). This tool allows you to filter messages by author and hashtags, and then export the selected messages to an XML file.

**Live Application:** [https://tg-chat-processor.timurai.tech/](https://tg-chat-processor.timurai.tech/)

## How to Use

1.  **Export your Telegram chat history.**
    *   Open the Telegram Desktop application.
    *   Go to the chat you want to export.
    *   Click on the three dots in the top right corner and select "Export chat history".
    *   Choose "JSON" as the format.
    *   Deselect all media types to get a `result.json` file.
    *   Once the export is complete, you will find a `result.json` file in the specified folder.

2.  **Use the Telegram Chat Processor.**
    *   Open the [live application](https://tg-chat-processor.timurai.tech/).
    *   Drag and drop the `result.json` file into the designated area, or click to select the file.
    *   The tool will process the file and display the messages, authors, and hashtags.
    *   Use the checkboxes to filter the messages by author and hashtag.
    *   Use the options at the top to customize the output.
    *   The processed output will be displayed in the "Processed Output" panel.
    *   You can copy the output to your clipboard or save it as an XML file.

## Features

*   **Client-Side Processing:** All processing is done in your browser. Your data is not sent to any server.
*   **Filter by Author:** Filter messages by selecting one or more authors.
*   **Filter by Hashtag:** Filter messages by selecting one or more hashtags.
*   **Include/Exclude Reactions:** Choose whether to include message reactions in the output.
*   **Show/Hide Summary:** Toggle the visibility of the message summary panel.
*   **Preview Output:** Limit the output to the first 100 messages for a quick preview.
*   **Include/Exclude Dates:** Choose whether to include message dates in the output.
*   **Anonymize Users:** Replace author names with sequential user IDs for privacy.
*   **Copy to Clipboard:** Copy the processed XML output to your clipboard.
*   **Save as XML:** Save the processed output as a `processed_chat.xml` file.

## Contributing

This is an open-source project, and contributions are welcome. If you have a suggestion or want to report a bug, please open an issue on the GitHub repository.

If you want to contribute to the code, please follow these steps:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Make your changes.
4.  Submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
