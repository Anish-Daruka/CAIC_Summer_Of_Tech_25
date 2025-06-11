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



