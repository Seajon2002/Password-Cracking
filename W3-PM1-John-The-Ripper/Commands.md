# John the Ripper – Commands & Practical Workflow

## Environment
- Operating System: Kali Linux
- Tool: John the Ripper
- Wordlist: RockYou

## 1. Execute Password Cracking

```bash
john --wordlist=/usr/share/wordlists/rockyou.txt pdf3.txt
```

### Command Explanation

| Option | Description |
|---|---|
| `john` | Launches John the Ripper |
| `--wordlist` | Specifies the wordlist |
| `rockyou.txt` | Dictionary file |
| `pdf3.txt` | File containing the extracted PDF hash |

## 2. Practical Result

- PDF hash successfully loaded.
- Dictionary attack executed.
- Matching password candidate identified.
- Cracking session completed successfully.

## 3. Learning Outcome

Learned how to extract PDF hashes and perform dictionary-based password auditing using John the Ripper.

**Note:** Commands are documented for authorized lab use only.
