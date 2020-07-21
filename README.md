---


---

<h1 id="api-2u-epicspot">API 2U Epicspot</h1>
<p><strong>Base URL</strong>: <a href="http://phpstack-371980-1373330.cloudwaysapps.com/hotsite/api_2u/api/v1/index.php">http://phpstack-371980-1373330.cloudwaysapps.com/hotsite/api_2u/api/v1/index.php</a></p>
<h1 id="routes">Routes</h1>
<ul>
<li><strong>Method POST</strong></li>
<li>Path: <strong>/</strong></li>
<li><strong>Consumes type:</strong> application/json</li>
<li><strong>Return type:</strong> application/json</li>
<li><strong>Charset</strong> utf-8</li>
<li>Query String Parameters:</li>
</ul>
<ol>
<li><em>id</em><br>
<strong>Type</strong>: integer<br>
<strong>required</strong>: false</li>
<li><em>endereco</em><br>
<strong>Type</strong>: string<br>
<strong>required</strong>: false</li>
<li><em>cidade</em><br>
<strong>Type</strong>: string<br>
<strong>required</strong>: false</li>
<li><em>estado</em><br>
<strong>Type</strong>: string<br>
<strong>required</strong>: false</li>
<li><em>bairro</em><br>
<strong>Type</strong>: string<br>
<strong>required</strong>: false</li>
<li><em>cep</em><br>
<strong>Type</strong>: string<br>
<strong>required</strong>: false</li>
<li><em>quartos</em><br>
<strong>Type</strong>: integer<br>
<strong>required</strong>: false</li>
<li><em>valorVendaMin</em><br>
<strong>Type</strong>: integer<br>
<strong>required</strong>: false</li>
<li><em>valorVendaMax</em><br>
<strong>Type</strong>: integer<br>
<strong>required</strong>: false</li>
<li><em>alugar</em><br>
<strong>Type</strong>: boolean<br>
<strong>required</strong>: false<br>
<strong>1</strong> to TRUE, <strong>0</strong> to FALSE</li>
<li><em>vender</em><br>
<strong>Type</strong>: boolean<br>
<strong>required</strong>: false<br>
<strong>1</strong> to TRUE, <strong>0</strong> to FALSE</li>
<li><em>piscina</em><br>
<strong>Type</strong>: boolean<br>
<strong>required</strong>: false<br>
<strong>1</strong> to TRUE, <strong>0</strong> to FALSE</li>
</ol>
<p>Return body:<br>
Type: <strong>Array</strong></p>
<pre class=" language-json"><code class="prism  language-json"><span class="token punctuation">{</span>
       <span class="token string">"id"</span><span class="token punctuation">:</span> <span class="token string">"12"</span><span class="token punctuation">,</span>
       <span class="token string">"titulo"</span><span class="token punctuation">:</span> <span class="token string">"Apto 3 dorms | frente para shopping Shibata"</span><span class="token punctuation">,</span>
       <span class="token string">"descricao"</span><span class="token punctuation">:</span> <span class="token string">"Belíssimo Apto 3 dorms com armários planejados, suite, sala dois ambientes, ar condicionado, cozinha com armários planejados, lavabo, wc social, varanda gourmet, 2 vagas de garagem  Excelente localização em frente ao Shopping Shibata, fácil acesso a Dutra e Anel Viário.  Estuda-se permuta de menor valor.  Cauane Ribeiro| Corretora de Imóveis | Creci 199.892-F  (12) &lt;a href=\"#\" class=\"sc-57pm5w-0 XtcoW\"&gt;9971... ver número&lt;/a&gt; (WhatsApp 24h)"</span><span class="token punctuation">,</span>
       <span class="token string">"endereco"</span><span class="token punctuation">:</span> <span class="token string">"Rua Shizuko Iida"</span><span class="token punctuation">,</span>
       <span class="token string">"cidade"</span><span class="token punctuation">:</span> <span class="token string">"São José dos Campos"</span><span class="token punctuation">,</span>
       <span class="token string">"estado"</span><span class="token punctuation">:</span> <span class="token string">"SP"</span><span class="token punctuation">,</span>
       <span class="token string">"bairro"</span><span class="token punctuation">:</span> <span class="token string">"Jardim América"</span><span class="token punctuation">,</span>
       <span class="token string">"numero"</span><span class="token punctuation">:</span> <span class="token keyword">null</span><span class="token punctuation">,</span>
       <span class="token string">"complemento"</span><span class="token punctuation">:</span> <span class="token keyword">null</span><span class="token punctuation">,</span>
       <span class="token string">"cep"</span><span class="token punctuation">:</span> <span class="token string">"12235051"</span><span class="token punctuation">,</span>
       <span class="token string">"pais"</span><span class="token punctuation">:</span> <span class="token string">"BR"</span><span class="token punctuation">,</span>
       <span class="token string">"quartos"</span><span class="token punctuation">:</span> <span class="token string">"3"</span><span class="token punctuation">,</span>
       <span class="token string">"alugar"</span><span class="token punctuation">:</span> <span class="token keyword">null</span><span class="token punctuation">,</span>
       <span class="token string">"vender"</span><span class="token punctuation">:</span> <span class="token keyword">null</span><span class="token punctuation">,</span>
       <span class="token string">"valor_aluguel"</span><span class="token punctuation">:</span> <span class="token keyword">null</span><span class="token punctuation">,</span>
       <span class="token string">"valor_venda"</span><span class="token punctuation">:</span> <span class="token string">"540000.00"</span><span class="token punctuation">,</span>
       <span class="token string">"oferta"</span><span class="token punctuation">:</span> <span class="token keyword">null</span><span class="token punctuation">,</span>
       <span class="token string">"area"</span><span class="token punctuation">:</span> <span class="token string">""</span><span class="token punctuation">,</span>
       <span class="token string">"piscina"</span><span class="token punctuation">:</span> <span class="token keyword">null</span><span class="token punctuation">,</span>
       <span class="token string">"banheiros"</span><span class="token punctuation">:</span> <span class="token string">"3"</span><span class="token punctuation">,</span>
       <span class="token string">"tipo_imovel"</span><span class="token punctuation">:</span> <span class="token string">"Apartamentos"</span><span class="token punctuation">,</span>
       <span class="token string">"latitude"</span><span class="token punctuation">:</span> <span class="token string">"-23.2333917"</span><span class="token punctuation">,</span>
       <span class="token string">"longitude"</span><span class="token punctuation">:</span> <span class="token string">"-45.8969557"</span><span class="token punctuation">,</span>
       <span class="token string">"link_imovel"</span><span class="token punctuation">:</span> <span class="token string">"https://sp.olx.com.br/vale-do-paraiba-e-litoral-norte/imoveis/apto-3-dorms-frente-para-shopping-shibata-741277086"</span><span class="token punctuation">,</span>
       <span class="token string">"link_img"</span><span class="token punctuation">:</span> <span class="token string">"https://img.olx.com.br/images/82/825005635001793.jpg"</span><span class="token punctuation">,</span>
       <span class="token string">"agente_nome"</span><span class="token punctuation">:</span> <span class="token keyword">null</span><span class="token punctuation">,</span>
       <span class="token string">"agente_creci"</span><span class="token punctuation">:</span> <span class="token keyword">null</span><span class="token punctuation">,</span>
       <span class="token string">"agente_img"</span><span class="token punctuation">:</span> <span class="token keyword">null</span><span class="token punctuation">,</span>
       <span class="token string">"agente_fone"</span><span class="token punctuation">:</span> <span class="token keyword">null</span><span class="token punctuation">,</span>
       <span class="token string">"agente_email"</span><span class="token punctuation">:</span> <span class="token keyword">null</span><span class="token punctuation">,</span>
       <span class="token string">"ativo"</span><span class="token punctuation">:</span> <span class="token string">"1"</span>
   <span class="token punctuation">}</span><span class="token punctuation">,</span>
</code></pre>

