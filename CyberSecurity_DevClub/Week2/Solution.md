# CTF Challenge Writeup

---

## 1. Classic Cipher

*This appears to be a basic classical cipher challenge.*

![Classic Cipher](caeser.png)

---

## 2. Oui Oui Secret

By brute-forcing, we get a nearly correct result.

Changing **B → L** in the key gives the correct output.

![Oui Oui Secret](secret.png)

---

## 3. Fair Play

As the name suggests, it’s likely a **Playfair cipher**.

Brute-forcing the key eventually reveals the flag.

![Fair Play](fair_play.png)

---

## 4. Weak RSA



Flag retrieved after decryption.

![Weak RSA](RSA1.png)
![Weak RSA](RSA2.png)


---

## 5. XOR Cipher

Looks like a **repeating-key XOR** encryption.

Key observed to repeat (like `"sand"`).

Decryption by XORing the ciphertext with the repeating key gives the flag.

![XOR Cipher](XOR.png)



## 6. Chameleon image

Binwalk the file,gives that it is a zip file

![chameleon_solution](mystery_file.png)

## 7. Sounds_of_secret

![morse](morse1.png)

Audio steganogram suggests that it is a morse code

![morse](morse2.png)


## 8. Chropped Antique

Extracting with pdfimages gives the full image

![cropped](cropped.png)


## 9. Evidence disk

scanning with foremost,reveals the flag

![foremost](evidence_disk.png)


## 10. network intrusion

![Network](network1.png)

A msg was send from 127.0.0.0 to 0.0.0.0,decoding the msg gives the flag

![Network](network2.png)