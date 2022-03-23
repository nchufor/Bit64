# Bit64

Base64 encoding and decoding data has many use cases. One being is ensuring data integrity when transferring data over the network, while another is storing Secrets in Kubernetes.

# Why Base64 Encode Data

Transferring an ASCII file over the network can cause corruption if not decoded correctly. The reason is ASCII files are string converted to bytes, and when those bytes are decoded incorrectly back to ASCII your data becomes corrupt.
