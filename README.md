# rfc
RFC reading memo




https://www.ietf.org/rfc.html

The Web Origin Concept
	https://www.ietf.org/rfc/rfc6454.txt

###########################################################
TCP  https://ja.wikipedia.org/wiki/Transmission_Control_Protocol
###########################################################


TRANSMISSION CONTROL PROTOCOL
	https://tools.ietf.org/html/rfc793


###########################################################
UDP   https://ja.wikipedia.org/wiki/User_Datagram_Protocol
###########################################################
User Datagram Protocol
	https://tools.ietf.org/html/rfc768

The Lightweight User Datagram Protocol (UDP-Lite)
	https://tools.ietf.org/html/rfc3828

Management Information Base for the User Datagram Protocol (UDP)


###########################################################
TLS   https://ja.wikipedia.org/wiki/User_Datagram_Protocol
###########################################################
Internet X.509 Public Key Infrastructure Certificate and Certificate Revocation List (CRL) Profile
	https://tools.ietf.org/html/rfc5280


###########################################################
HTTPS  https://ja.wikipedia.org/wiki/HTTPS
###########################################################
HTTP Over TLS
	https://tools.ietf.org/html/rfc2818

The Secure HyperText Transfer Protocol
	https://tools.ietf.org/html/rfc2660	


###########################################################
OpenID Connect
http://www.openid.or.jp/document/
###########################################################

JSON Web Token (JWT)
	OpenID Connect により発行される ID トークンは、JSON Web Token の一種であり以下で規定されている。
	https://tools.ietf.org/html/rfc7519

JSON Web Signature (JWS)
	https://tools.ietf.org/html/rfc7515

JSON Web Encryption (JWE)
	https://tools.ietf.org/html/rfc7516

JSON Web Key (JWK)
	https://tools.ietf.org/html/rfc7517

JSON Web Algorithms (JWA)
	https://tools.ietf.org/html/rfc7518

###########################################################
OAuth2.0
###########################################################

この辺で詳しくまとめられている。
	http://qiita.com/TakahikoKawasaki/items/185d34814eb9f7ac7ef3

特に重要なのは上の２つ
The OAuth 2.0 Authorization Framework
	OAuth2.0仕様の本体となっていてAuthorization Code Grant, Implicit Grant, Resource Owner Password Credentials Grant, Client Credentials Grantの４つを定義していて、リフレッシュトークンやアクセストークンを定義してりう。
	https://tools.ietf.org/html/rfc6749

The OAuth 2.0 Authorization Framework: Bearer Token Usage
	https://tools.ietf.org/html/rfc6750

OAuth 2.0 Threat Model and Security Considerations
	OAuth2.0の実装にあたりセキュリティーに関して考慮すべき実装点についてまとめられている。
	https://tools.ietf.org/html/rfc6819

OAuth 2.0 Token Revocation
	発行されたアクセストークンやリフレッシュトークンを取り消すための手段に関する規定
	https://tools.ietf.org/html/rfc7009

OAuth 2.0 Token Introspection
	アクセストークンやリフレッシュトークンの情報を取得するための手段に関する規定
	https://tools.ietf.org/html/rfc7662

Proof Key for Code Exchange by OAuth Public Clients
	認可コードフローにより発行された認可コードをクライアントアプリケーションが受け取る際、悪意のあるアプリケーションがその認可コードを横取りするという攻撃への対応策として取り入れられた仕様
	https://tools.ietf.org/html/rfc7636

Assertion Framework for OAuth 2.0 Client Authentication and Authorization Grants
	https://tools.ietf.org/html/rfc7521

Security Assertion Markup Language (SAML) 2.0 Profile for OAuth 2.0 Client Authentication and Authorization Grants
	https://tools.ietf.org/html/rfc7522

JSON Web Token (JWT) Profile for OAuth 2.0 Client Authentication and Authorization Grants
	https://tools.ietf.org/html/rfc7523

###########################################################
OAuth1.0
###########################################################
The OAuth 1.0 Protocol
	https://tools.ietf.org/html/rfc5849

###########################################################
HTTP   http://www.asahi-net.or.jp/~ax2s-kmtn/ref/status.html
###########################################################	

Hypertext Transfer Protocol -- HTTP/1.0
	https://tools.ietf.org/html/rfc1945

Hypertext Transfer Protocol -- HTTP/1.1

Hypertext Transfer Protocol -- HTTP/1.1
	https://tools.ietf.org/html/rfc2616

Hypertext Transfer Protocol (HTTP/1.1): Message Syntax and Routing
	https://tools.ietf.org/html/rfc7230	

###########################################################
最新WEB
###########################################################	
The WebSocket Protocol
	OAuth2.0(RFC6749)の策定を持って廃止された。
	https://tools.ietf.org/html/rfc6455

QUIC: A UDP-Based Secure and Reliable Transport for HTTP/2 draft-tsvwg-quic-protocol-00
	https://tools.ietf.org/html/draft-tsvwg-quic-protocol-00

HTTP State Management Mechanism
	https://tools.ietf.org/html/rfc6265




The application/json Media Type for JavaScript Object Notation (JSON)
 	https://tools.ietf.org/html/rfc4627

The Base16, Base32, and Base64 Data Encodings
 	https://tools.ietf.org/html/rfc4648

