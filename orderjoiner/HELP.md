./kafka-console-consumer \
     --bootstrap-server localhost:9092 \
     --topic order-enrich \
     --property print.key=true \
     --from-beginning

./kafka-console-producer \
     --broker-list localhost:9092 \
     --topic orders1 \
     --property "parse.key=true" \
     --property "key.separator=:" 
nacci:{"myId":"nacci","more":"fibo"} 


./kafka-console-producer \
     --broker-list localhost:9092 \
     --topic order-stuff \
     --property "parse.key=true" \
     --property "key.separator=:" 
nacci:{"extId":"nacci","stuff":"foo"} 