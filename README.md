# NetSleuth - IP & Domain Information Tool

NetSleuth is a user-friendly Python-based GUI tool that allows users to retrieve detailed information about both IP addresses and domain names. With its sleek interface, NetSleuth provides essential data such as IP location, ISP details, domain registration information, and much more.

## Features

- **IP Address Lookup**: Get comprehensive details about any IP address including location, organization, and more.
- **Domain Name Lookup**: Retrieve whois information for domain names including registrar, creation and expiration dates, name servers, and country.
- **Responsive GUI**: NetSleuth is built with a modern, easy-to-use graphical interface that ensures a smooth user experience.
- **Fast and Lightweight**: Multi-threading ensures the tool remains responsive during information retrieval.

## Screenshot
![Screenshot 2024-10-20 112156](https://github.com/user-attachments/assets/f205e034-6d38-4631-a034-474a6feeae05)


## Getting Started

### Prerequisites

Ensure you have the following installed:
- Python 3.x
- Required Python libraries: `whois`, `requests`, `tkinter`

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/anurag-singh123/NetSleuth
   cd NetSleuth
   ```

2. Install the required Python libraries:
   ```bash
   pip install requests python-whois
   ```

3. Run the application:
   ```bash
   python NetSleuth.py
   ```

### How to Use

1. Run the program and the **NetSleuth** window will appear.
2. Enter either an IP address or a domain name in the input field.
3. Click on the **Get Info** button to retrieve the details.
4. The results will be displayed in the output box, categorized by **IP Information** or **Domain Information** based on the input.

### Example

- **IP Lookup**: You can enter an IP like `8.8.8.8` (Google’s public DNS) to get information about the location, organization, etc.
- **Domain Lookup**: Enter a domain like `example.com` to fetch the domain’s registration details.

## Technologies Used

- **Python**: The core programming language used.
- **Tkinter**: The GUI library used to create the interface.
- **Requests**: Used to retrieve data from the IPInfo API for IP address lookup.
- **Whois**: Used to fetch whois information for domain names.

## Contributing

Contributions are welcome! If you would like to add more features, improve the user interface, or optimize performance, please feel free to create a pull request.

### Steps to Contribute:

1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions, suggestions, or feedback, feel free to reach out:

- **GitHub**: https://github.com/anurag-singh123
- **Email**: anurag.singh01018@gmail.com
