# Vohala_Data_Transfer_Calculator


This is a simple web tool that calculates the estimated time required to transfer a file over a network based on the file size and the bandwidth of the network connection. The tool allows users to input the file size, choose the unit (KB, MB, or GB), and specify the bandwidth in Mbps to calculate the transfer time.
Features

    Input file size and select the appropriate unit (KB, MB, or GB).
    Input the network bandwidth in Mbps (Megabits per second).
    Instantly calculates the estimated time required for the file transfer in hours, minutes, and seconds.
    Easy-to-use interface with clear labels and feedback.

Usage

    Clone the repository or download the Data_Transfer_Calculator.html file.
    Open the Data_Transfer_Calculator.html file in any modern web browser.
    Enter the file size and select the unit (KB, MB, or GB).
    Enter the bandwidth in Mbps.
    Click the "Calculate" button to get the estimated transfer time.

Example

For example, if you have:

    A file size of 500 MB
    Network bandwidth of 100 Mbps

The calculator will estimate the transfer time as per your input.
Code Explanation

    HTML: The structure of the page, containing input fields for file size, bandwidth, and a dropdown for selecting file size units.
    CSS: Basic styling is used to make the interface clean and readable. It includes styling for inputs, buttons, and the result display.
    JavaScript: The logic behind calculating the transfer time is implemented in JavaScript. The file size is converted to bits depending on the unit selected (KB, MB, or GB), and the time is calculated by dividing the file size by the bandwidth.

Calculation Formula:

scss

Transfer Time (seconds) = (File Size in bits) / (Bandwidth in bits per second)

Where:

    File size is converted to bits based on the unit selected (KB, MB, GB).
    Bandwidth is given in Mbps (Megabits per second), so file size is divided by bandwidth to get the transfer time in seconds. This is then converted to hours, minutes, and seconds for better readability.

Contributing

Feel free to fork this repository and contribute by submitting pull requests with improvements or additional features.
