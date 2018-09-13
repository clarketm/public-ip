# public-ip
A simple public IP address API.
<br>
<br>
<a href="https://github.com/clarketm/public-ip">
  <p align="center"><img width="20%" src="/ip.png" /></p>
</a>

## API

[**GET**](https://ipv4.travismclarke.com/) public *IPv4* address

```bash
$ curl -XGET -4 "https://ipv4.travismclarke.com/"
```
```bash
167.88.112.238
```


[**GET**](https://ipv6.travismclarke.com/) public *IPv6* address

```bash
$ curl -XGET -6 "https://ipv6.travismclarke.com/"
```
```bash
2604:a781:2:b1::13:4101
```

## License

MIT &copy; [**Travis Clarke**](https://blog.travismclarke.com/)
