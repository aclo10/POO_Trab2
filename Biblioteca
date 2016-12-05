public class Biblioteca {

	private Usuario[] usuarios;
	private Item[] itens;
	private int nUsuarios;
	private int nItens;
	private Usuario usuarioAtivo; // necessÃ¡rio?

	public Biblioteca() {
		this.usuarios = new Usuario[10]; // valor arbitrÃ¡rio
		this.itens = new Itens[100]; // valor arbitrÃ¡rio
		this.nUsuarios = -1;
		this.nItens = -1;
	}

	public void cadastrarUsuario(String _nome, String _matricula, boolean _su) {
		if(nUsuarios < 10) {
			this.nUsuarios++;
			if(su) {
				this.usuarios[this.nUsuarios] = new Operador(_nome, _matricula);
			} else {
				this.usuarios[this.nUsuarios] = new UsuarioComum(_nome, _matricula);
			}
		}
	}

	public void cadastraItem(String _nome, String _codigo, String _editora) {
		Item novo = this.usuarioAtivo.cadastraItem(_nome, _codigo, _editora);
		this.nItens++;
		this.itens[this.nItens] = novo;
	}

	public void cadastraItem(String _revista, String _codigo, String _editora, String _semana) {
		Item novo = this.usuarioAtivo.cadastraItem(_nome, _codigo, _editora, _semana);
		this.nItens++;
		this.itens[this.nItens] = novo;
	}
        
        public void cadastraItem(String _livro, String _codigo, String _editora, String _semana) {
		Item novo = this.usuarioAtivo.cadastraItem(_nome, _codigo, _editora, _semana);
		this.nItens++;
		this.itens[this.nItens] = novo;
	}
}
    
}
