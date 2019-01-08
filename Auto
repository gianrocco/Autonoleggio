public class Auto extends Categoria {
	private String modello;
	private int cilindrata;
	private String colore;
	private int immatricolazione;
	private String casaAutomobilistica;
	private String targa;
	private boolean disponibilita;
	private int id=0;
		private Auto(String nomeCategoria, double pg, double ps, double pm, String modello, int cilindrata, String colore, int immatricolazione, String casaAutomobilistica, String targa) {
		super(nomeCategoria,pg, ps, pm);
		this.modello = modello;
		this.cilindrata = cilindrata;
		this.colore = colore;
		this.immatricolazione = immatricolazione;
		this.casaAutomobilistica = casaAutomobilistica;
		this.targa=targa;
		disponibilita=true;
		id=incrementaId(id);
		}
		 		
		public static Auto autoBuilder() {
			
		}
		
		public String getTarga() {
			return targa;
		}
		public void setTarga(String targa) {
			this.targa = targa;
		}
		private int incrementaId(int id) {
				id++;
			return id;
		}
		
		public String getModello() {
			return modello;
		}
		public int getId() {
			return id;
		}
		
		public void setModello(String modello) {
			this.modello = modello;
		}
		public int getCilindrata() {
			return cilindrata;
		}
		public void setCilindrata(int cilindrata) {
			this.cilindrata = cilindrata;
		}
		public String getColore() {
			return colore;
		}
		public void setColore(String colore) {
			this.colore = colore;
		}
		public int getImmatricolazione() {
			return immatricolazione;
		}
		public boolean setImmatricolazione(int immatricolazione) {
			if(immatricolazione>1900&&immatricolazione<2100) {
			this.immatricolazione = immatricolazione;
			return true;
			}else {
				System.out.println("Inserisci un anno valido");
				return false;
			}
		}
		public String getCasaAutomobilistica() {
			return casaAutomobilistica;
		}
		public void setCasaAutomobilistica(String casaAutomobilistica) {
			this.casaAutomobilistica = casaAutomobilistica;
		}
		public boolean isDisponibilita() {
			return disponibilita;
		}
		public void setDisponibilita(boolean disponibilita) {
			this.disponibilita = disponibilita;
		}
		@Override
		public String toString() {
			return "Auto [modello=" + modello + ", cilindrata=" + cilindrata + ", colore=" + colore
					+ ", immatricolazione=" + immatricolazione + ", casaAutomobilistica=" + casaAutomobilistica
					+ ", targa=" + targa + ", disponibilita=" + disponibilita + "]";
		}
}
