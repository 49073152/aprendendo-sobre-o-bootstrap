# aprendendo-sobre-o-bootstrap
<!DOCTYPE html>
<html>
    <head>
        <title>Trabalhando com Css Bootstrap</title>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
	<!-- CSS only -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
    </head>
    <body>
        <div class="container-fluid p-5 bg-secondary text-white text-center">
          <h1>Minha primeira página com Bootstrap</h1>
          <p>Redimensione esta página e veja o efeito responsivo do bootstrap</p>
        </div>
        
        <div class="container">
          <div class="row">
            <div class="col-sm-4">
              <h3>Coluna 1</h3>
              <p>Lorem ipsum dolor..</p>
            </div>
            <div class="col-sm-4">
              <h3>Coluna 2</h3>
              <p>Lorem ipsum dolor..</p>
            </div>
            <div class="col-sm-4">
              <h3>Coluna 3</h3>
              <p>Lorem ipsum dolor..</p>
            </div>
          </div>
		  <div>
			<form>
				<div class="mb-3 mt-3">
				<label class="form-label">Nome: <input type='text' 
                                        class="form-control"
				                                placeholder='informe seu nome' 
									                      name='nome'>
				</label>
				</div>
				<div class="mb-3 mt-3">
				<label class="form-label">Idade: <input type='number' name='idade' class="form-control"></label>
				</div>
				<input type="submit" value="Envio" class="btn btn-primary">
			</form>
		</div>
        </div>
		
    </body>
</html>
