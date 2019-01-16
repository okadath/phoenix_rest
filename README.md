creando una API rest desde elixir

versiones:

	$elixir -v
	Elixir 1.7.4 (compiled with Erlang/OTP 20)
	$ mix phoenix.new -v
	Phoenix v1.2.5

crear:

	mix phx.new busi_api --no-html --no-webpack



Python-Elixir
===
crear proyecto:

	mix new elixir_python_qrcode

agregar en el mix.exs la dependencia:
	
	defp deps do
	    [
	      {:erlport, "~> 0.9"},
	    ]
	  end

instalar dependencias:
	
	mix deps.get

en lib viven los archivos, agregar helper.ex su codigo, para castear los valores de las funciones d epython

luego en el main agregar


	

testeando con erlport, hay que cambiarle a la documentacion
inicia con : y se llama con . y las variables se pasan con :

	{ok, p} = :python.start([{:python_path, "/"},{:python, "python3"}])






