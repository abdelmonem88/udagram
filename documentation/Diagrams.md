# Diagrams

### APP process diagram

( Client ) - Send Request ->
[ S3 Bucket ] - Send Data ->
[ EB Server ] - Check data and connect to DB ->
[ Database ] - Response Back to ->
[ EB Server ] - Return Data ->
[ S3 Bucket ] - Vieweing to ->
( Client )

### Deploy process diagram

(CircleCi) - Connect to GitHub -> ( Github ) - Send Data -> ( CircleCi ) - Build Data & Deploy -> [AWS S3] & [EB Environment] -> Return Data to servers
