# StartecTextBox
TextBox com várias funções e designers para ser usado em WindowsForms

funções:<br>
BorderRadius -> (int), Arredondamento da borda do elemento <br>
BorderFocusColor -> (Color) Cor da borda quando o elemento está selecionado<br>
MaskCpf -> (bool) Cria uma mascara de cpf e cnpj para o campo<br>
maskReal -> (bool) Cria uma mascara de real para o campo<br>
maskData -> (bool) Cria uma mascara de data para o campo<br>
maskTel -> (bool) Cria uma mascara de telefone para o campo<br>
Multiline -> (bool) Cria um campo de varias linhas para o elemento<br><br>


pode ser adicionado a qualquer projeto winforms, o projeto terá novas atualizações,mas estas feats citadas acima estão funcionando!<br><br>

exemplos:<br>

            
            StartecTextBox example = new StartecTextBox();
            example.Width = 200;
            example.Font = new Font(FontFamily.GenericSerif, 20);
            example.ForeColor = Color.Black;
            example.BorderColor = this.BackColor;
            example.MaskCpf = true;
            example.BorderRadius = 8;
            example.BorderFocusColor = Color.FromArgb(215, 250, 25);
            example.Location = new Point(0,0);

            StartecTextBox example = new StartecTextBox();
            example.Width = 200;
            example.Font = new Font(FontFamily.GenericSerif, 20);
            example.ForeColor = Color.Black;
            example.BorderColor = this.BackColor;
            example.MaskReal = true;
            example.BorderRadius = 8;
            example.BorderFocusColor = Color.FromArgb(215, 250, 25);
            example.Location = new Point(0,0);

            StartecTextBox example = new StartecTextBox();
            example.Width = 200;
            example.Font = new Font(FontFamily.GenericSerif, 20);
            example.ForeColor = Color.Black;
            example.BorderColor = this.BackColor;
            example.MaskTel = true;
            example.BorderRadius = 8;
            example.BorderFocusColor = Color.FromArgb(215, 250, 25);
            example.Location = new Point(0,0);
