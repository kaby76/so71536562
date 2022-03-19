# Generated code from trgen 0.15.0
GENERATED = ArithmeticParser.cs ArithmeticLexer.cs 
default:
	dotnet restore
	dotnet build
run:
	trwdog dotnet run $(RUNARGS)
clean:
	dotnet clean
	rm -rf bin obj
test:
	bash test.sh
