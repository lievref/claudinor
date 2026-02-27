# Campos de `snv.snv_202602a_ul_Passos_edit`

Essa tabela é a cópia filtrada (UL='Passos') da versão mais recente do SNV (2026-02). Serve como base editável enquanto `snv.snv_202602a_ul_Passos` permanece como referência. Abaixo seguem os campos e os respectivos tipos de dados:

| Campo | Tipo | Observações |
| --- | --- | --- |
| `gid` | `integer` | Identificador sequencial gerado pelo PostGIS. |
| `id_trecho_` | `double precision` | ID numérico do trecho. |
| `vl_br` | `character varying(3)` | Valor B/R (sigla). |
| `sg_uf` | `character varying(2)` | Sigla da unidade federativa. |
| `nm_tipo_tr` | `character varying(254)` | Nome do tipo de trecho. |
| `sg_tipo_tr` | `character varying(1)` | Sigla curta do tipo. |
| `desc_coinc` | `character varying(254)` | Descrição da coincidência. |
| `vl_codigo` | `character varying(20)` | Código de identificação. |
| `ds_local_i` | `character varying(254)` | Descrição do local inicial. |
| `ds_local_f` | `character varying(254)` | Descrição do local final. |
| `vl_km_inic` | `numeric` | Quilometragem inicial. |
| `vl_km_fina` | `numeric` | Quilometragem final. |
| `vl_extensa` | `numeric` | Extensão do trecho. |
| `ds_sup_fed` | `character varying(254)` | Descrição da superintendência federal. |
| `ds_obra` | `character varying(3)` | Tipo de obra. |
| `ul` | `character varying(254)` | Unidade local (neste caso, sempre 'Passos'). |
| `ds_coinc` | `character varying(254)` | Descrição da coincidência. |
| `ds_tipo_ad` | `character varying(254)` | Tipo administrativo descrito. |
| `ds_ato_leg` | `character varying(254)` | Ato legal relacionado. |
| `est_coinc` | `character varying(254)` | Estado da coincidência. |
| `sup_est_co` | `character varying(254)` | Supervisão do estado de coincidência. |
| `ds_jurisdi` | `character varying(254)` | Jurisdição. |
| `ds_superfi` | `character varying(254)` | Tipo de superfície. |
| `ds_legenda` | `character varying(254)` | Texto complementar. |
| `sg_legenda` | `character varying(254)` | Sigla da legenda. |
| `leg_multim` | `character varying(254)` | Legenda multimodal. |
| `versao_snv` | `character varying(15)` | Versão do SNV (ex: `202602A`). |
| `id_versao` | `double precision` | ID numérico da versão. |
| `marcador` | `character varying(254)` | Campo auxiliar para marcação. |
| `geom` | `geometry(MultiLineString,4674)` | Geometria topológica em SIRGAS 2000; índice `snv_202602a_ul_passos_edit_geom_idx`. |

Se quiser, posso transformar isso num resumo no GitHub (usar run-save) para ficar registrado junto com os outros resumos. Deseja que eu salve como outro arquivo de resumo?