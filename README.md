# dns


## dig

### Get informations about mail mx of a domaine

```bash
dig mx mydomaine.com
```

### Get short informations

```bash
dig mx midia.fr +short
10 mail.midia.fr.
20 mail1.midia.fr.
```

### Get Address

```bash
dig mydomaine.com A
```

### Get the hostnames

```bash
dig NS petitresto.fr +short
```
