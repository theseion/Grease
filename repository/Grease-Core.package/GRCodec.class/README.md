A codec defines how Seaside communicates without the outside world and how outside data is converted into the image (decoding) and back outside the image (encoding). The codec is essentially a stream factory that provides wrappers around standard streams. All streams do support binary mode for non-converted transfer.