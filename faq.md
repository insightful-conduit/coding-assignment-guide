### Coding Assignment: Frequently Asked Question

Here are some popular _frequently asked questions_ about the coding assignment.

---

#### What is a _JWT_?

Please research _JWT_ if you are not familiar with the JWT concept, structure or usage.

#### What `{id}` can be used in the given endpoint?

You may use any six-digit numeric string.

Valid:

- 000000
- 182511
- 872631

Invalid:

- abcdef
- 1234567
- 12345

#### What does an example payload look like?

Please decode the payload to find the exact structure. For an example, a payload _may_ look something like this:

```json
{
  "inboxId": "8d969eef6ecad3c29a3a629280e686cf0c3f5d5a86aff3ca12020c923adc6c92",
  // more fields ...
  "messages": {
    "aafb3b0f969da8e7e27691d5ce1bdf906e64015af67c0d7a109f2e924ec4dde8": {
      "messageContent": "Tea oporteat corrumpit quo."
      // more fields ...
    }
    // more entries ...
  }
}
```

#### How is the API built?

Thanks for your curiosity! For the interview coding assignment, this is not an important aspect.

Still want to know more?

Althought left intentionally unlinked, you will find the source code to the API in another repository nearby.

#### What is `now.sh`?

Thanks for your curiosity! For the interview coding assignment, this is not an important aspect.

That said, `now` is a product from [Zeit](https://zeit.co/) that allows for easy serverless deployments outside of the traditional Amazon, Google and Microsoft clouds.

#### I have a question not answered here, what should I do?

Please open an issue in this repository's issue tracker and ask your question. If it meets FAQ criteria, it will eventually become a part of this document. Otherwise, it may be answered privately, or removed.

#### I found a bug or unexpected edge case, what should I do?

Please open an issue in this repository's issue tracker and report it.
