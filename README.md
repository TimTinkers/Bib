# Bib
Bib is a simple command-line SSH connection manager.

## Usage
Generally, to connect to a server, first you *add* it then you *connect* to it.
- `add`; stores a new connection with Bib for using later:
  ```
  bib add <name> <host>
    <-p> or
    <-pf> <password file> or
    <-kf> <key file>
  ```
- `remove` (`rm`); removes a connection stored with Bib: `bib remove <name>`
- `list` (`ls`); lists connections that are available for Bib: `bib list`
- `connect` (`con`); connect to a stored connection given its name: `bib connect <name>`
- `help` (`h`); displays the available commands: `bib help`
