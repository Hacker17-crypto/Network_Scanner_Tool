# Network Scanner Tool

Network Scanner Tool is a lightweight C# console app that maps out devices on your local network. It's handy for web developers who need to confirm which servers or containers are reachable in a dev environment. Use it responsibly and only on networks you control.

## Why Web Developers Might Use It

- Quickly see which machines are active on your development subnet
- Verify that local servers and test containers are accessible
- Learn more about network discovery while troubleshooting

## Building and Running

1. Install the .NET SDK if you don't have it yet.
2. Build the project:
   ```bash
   dotnet build
   ```
3. Run the scanner:
   ```bash
   dotnet run
   ```
   The tool will list devices it finds on your network.

## Ethical Notice

Scanning networks without permission is unethical and can be illegal. This tool is for educational use—only scan networks you own or are authorized to test.

## License

Provided as-is for learning purposes.
