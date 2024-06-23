An example preference document may look like:

<!-- If deleting this comment, the code formatting will be errornous. -->

```turtle
@prefix : <urn:solid:mpc#>

[]
    :trustedComputationServer
        [ schema:url "http://localhost:8010" ],
        [ schema:url "http://localhost:8011" ],
        [ schema:url "http://localhost:8012" ];
    :trustedEncryptionServer
        [ schema:url "http://localhost:8000";
          :userId "https://web.id/alice#me" ],
        [ schema:url "http://localhost:8001";
          :userId "can-also-be-some-special-id-for-this-encryption-agent-service" ].
```