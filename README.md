[![Go Report Card](https://goreportcard.com/badge/github.com/appscode/onessl)](https://goreportcard.com/report/github.com/appscode/onessl)

# onessl
Simple CLI to generate SSL certificates on any platform.


## Available Commands
* [onessl create](/docs/reference/onessl_create.md)	 - create PKI
  * [onessl create ca-cert](/docs/reference/onessl_create_ca-cert.md)	 - Create CA cert/key pair
  * [onessl create client-cert](/docs/reference/onessl_create_client-cert.md)	 - Generate client certificate pair
  * [onessl create server-cert](/docs/reference/onessl_create_server-cert.md)	 - Generate server certificate pair
* [onessl get](/docs/reference/onessl_get.md)	 - Get stuff
  * [onessl get ca-cert](/docs/reference/onessl_get_ca-cert.md)	 - Prints self-sgned CA certificate from PEM encoded RSA private key


## Contribution guidelines
Want to help improve onessl? Please start [here](/CONTRIBUTING.md).

---

**onessl binary collects anonymous usage statistics to help us learn how the software is being used and how we can improve it. To disable stats collection, run the operator with the flag** `--analytics=false`.

---

## Support

We use Slack for public discussions. To chit chat with us or the rest of the community, join us in the [AppsCode Slack team](https://appscode.slack.com/messages/C0XQFLGRM/details/) channel `#general`. To sign up, use our [Slack inviter](https://slack.appscode.com/).

If you have found a bug with Voyager or want to request for new features, please [file an issue](https://github.com/appscode/voyager/issues/new).
