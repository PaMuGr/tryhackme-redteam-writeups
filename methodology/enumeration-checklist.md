# Enumeration Checklist

## Network Enumeration

- nmap -sC -sV <target>
- Full TCP scan if necessary
- Identify exposed services
- Check versions for vulnerabilities

## Web Enumeration

- Inspect source code
- Directory brute force
- Parameter fuzzing

## Credential Testing

- Default credentials
- Password reuse
- SSH brute force (only when justified)

## Privilege Escalation

- sudo -l
- Writable configuration files
- Kernel version
- Capabilities