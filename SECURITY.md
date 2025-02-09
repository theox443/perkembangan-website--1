class SecurityPolicy:
    def __init__(self, supported_versions):
        self.supported_versions = supported_versions

    def is_version_supported(self, version):
        return version in self.supported_versions

    def display_supported_versions(self):
        print("Versi yang didukung:")
        for version in self.supported_versions:
            print(f"- {version}")

def main():
    # Daftar versi yang didukung
    supported_versions = 
| Version | Supported          |
| ------- | ------------------ |
| 5.1.x   | :white_check_mark: |
| 5.0.x   | :x:                |
| 4.0.x   | :white_check_mark: |
| < 4.0   | :x:                |


    #SecurityPolicy
    policy = SecurityPolicy(supported_versions)
    policy.display_supported_versions()
    user_version = input("Masukkan versi yang ingin Anda periksa: ")
    if policy.is_version_supported(user_version):
        print(f"Versi {user_version} didukung oleh kebijakan keamanan.")
    else:
        print(f"Versi {user_version} TIDAK didukung oleh kebijakan keamanan.")

if __name__ == "__main__":
    main()
python security_policy.py
| Version | Supported          |
| ------- | ------------------ |
| 5.1.x   | :white_check_mark: |
| 5.0.x   | :x:                |
| 4.0.x   | :white_check_mark: |
| < 4.0   | :x:                |

## Reporting a Vulnerability

Use this section to tell people how to report a vulnerability.

Tell them where to go, how often they can expect to get an update on a
reported vulnerability, what to expect if the vulnerability is accepted or
declined, etc.
