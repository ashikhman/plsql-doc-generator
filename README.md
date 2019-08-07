antlr -Dlanguage=Go -o parser Hello.g4 


# Generate
antlr4 -Dlanguage=Go -o parser PlSqlLexer.g4
antlr4 -Dlanguage=Go -o parser PlSqlParser.g4