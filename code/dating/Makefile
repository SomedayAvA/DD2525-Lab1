dating-server:
	$(TROUPE)/bin/troupec dating-server.trp -o ./out/dating-server.js
	node $(TROUPE)/rt/built/troupe.js -f=./out/dating-server.js --id=../ids/id-server.json --trustmap=../trustmaps/dating-server.json --aliases=aliases.json

dating-client1:
	$(TROUPE)/bin/troupec dating-client1.trp -o ./out/dating-client1.js
	node $(TROUPE)/rt/built/troupe.js -f=./out/dating-client1.js --id=../ids/id-client1.json --trustmap=../trustmaps/dating-client1.json --aliases=aliases.json

dating-client2:
	$(TROUPE)/bin/troupec dating-client2.trp -o ./out/dating-client2.js
	node $(TROUPE)/rt/built/troupe.js -f=./out/dating-client2.js --id=../ids/id-client2.json --trustmap=../trustmaps/dating-client2.json --aliases=aliases.json
