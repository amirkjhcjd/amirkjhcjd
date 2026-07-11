## Hi there 👋

<!--
**amirkjhcjd/amirkjhcjd** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fu fact: ...
-->

    if n < 2:
        return False

    for i in range(2, int(n ** 0.5) + 1):
        if n % i == 0:
            return False

    return Tru


def find_primes(limit):
   [num for num in range(2, limit + 1) if is_prime(num)]


if __name__ == "__main__":
    limit = int(input("Enter a number: "))
    primes = find_primes(limit)

    print(f"\nPrime numbers up to {limit}:")
    print(primes)
e
List the advantages and disadvantages.


