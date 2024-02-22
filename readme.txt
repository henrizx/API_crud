Criação de configaração
arquivo de configuração
json
----------------------------------------
configuração de banco
string de banco = protected override void OnConfiguring(DbContextOptionsBuilder options)
          => options.UseSqlServer("Server=localhost;Database=Products;User Id=sa;Password=@Sql2019;MultipleActiveResultSets=true;Encrypt=YES;TrustServerCertificate=Yes");
}
criacao de migrations
alterando as classes dentro do program para arquivos de classe paralelo