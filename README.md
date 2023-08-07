# estudo-dados-cancelamentos


![image](https://github.com/GCGusmao/estudos-dados-cancelamentos/assets/69112221/3aea9755-a57f-4197-939c-a8caf1844ff4)

[
	{
		"metadata": {
			"outputType": "display_data",
			"transient": {},
			"metadata": {}
		},
		"outputItems": [
			{
				"mimeType": "text/html",
				"data": "<div>\n<style scoped>\n    .dataframe tbody tr th:only-of-type {\n        vertical-align: middle;\n    }\n\n    .dataframe tbody tr th {\n        vertical-align: top;\n    }\n\n    .dataframe thead th {\n        text-align: right;\n    }\n</style>\n<table border=\"1\" class=\"dataframe\">\n  <thead>\n    <tr style=\"text-align: right;\">\n      <th></th>\n      <th>idade</th>\n      <th>sexo</th>\n      <th>tempo_como_cliente</th>\n      <th>frequencia_uso</th>\n      <th>ligacoes_callcenter</th>\n      <th>dias_atraso</th>\n      <th>assinatura</th>\n      <th>duracao_contrato</th>\n      <th>total_gasto</th>\n      <th>meses_ultima_interacao</th>\n      <th>cancelou</th>\n    </tr>\n  </thead>\n  <tbody>\n    <tr>\n      <th>0</th>\n      <td>30.0</td>\n      <td>Female</td>\n      <td>39.0</td>\n      <td>14.0</td>\n      <td>5.0</td>\n      <td>18.0</td>\n      <td>Standard</td>\n      <td>Annual</td>\n      <td>932.00</td>\n      <td>17.0</td>\n      <td>1.0</td>\n    </tr>\n    <tr>\n      <th>2</th>\n      <td>55.0</td>\n      <td>Female</td>\n      <td>14.0</td>\n      <td>4.0</td>\n      <td>6.0</td>\n      <td>18.0</td>\n      <td>Basic</td>\n      <td>Quarterly</td>\n      <td>185.00</td>\n      <td>3.0</td>\n      <td>1.0</td>\n    </tr>\n    <tr>\n      <th>5</th>\n      <td>51.0</td>\n      <td>Male</td>\n      <td>33.0</td>\n      <td>25.0</td>\n      <td>9.0</td>\n      <td>26.0</td>\n      <td>Premium</td>\n      <td>Annual</td>\n      <td>129.00</td>\n      <td>8.0</td>\n      <td>1.0</td>\n    </tr>\n    <tr>\n      <th>6</th>\n      <td>58.0</td>\n      <td>Female</td>\n      <td>49.0</td>\n      <td>12.0</td>\n      <td>3.0</td>\n      <td>16.0</td>\n      <td>Standard</td>\n      <td>Quarterly</td>\n      <td>821.00</td>\n      <td>24.0</td>\n      <td>1.0</td>\n    </tr>\n    <tr>\n      <th>7</th>\n      <td>55.0</td>\n      <td>Female</td>\n      <td>37.0</td>\n      <td>8.0</td>\n      <td>4.0</td>\n      <td>15.0</td>\n      <td>Premium</td>\n      <td>Annual</td>\n      <td>445.00</td>\n      <td>30.0</td>\n      <td>1.0</td>\n    </tr>\n    <tr>\n      <th>...</th>\n      <td>...</td>\n      <td>...</td>\n      <td>...</td>\n      <td>...</td>\n      <td>...</td>\n      <td>...</td>\n      <td>...</td>\n      <td>...</td>\n      <td>...</td>\n      <td>...</td>\n      <td>...</td>\n    </tr>\n    <tr>\n      <th>881661</th>\n      <td>42.0</td>\n      <td>Male</td>\n      <td>54.0</td>\n      <td>15.0</td>\n      <td>1.0</td>\n      <td>3.0</td>\n      <td>Premium</td>\n      <td>Annual</td>\n      <td>716.38</td>\n      <td>8.0</td>\n      <td>0.0</td>\n    </tr>\n    <tr>\n      <th>881662</th>\n      <td>25.0</td>\n      <td>Female</td>\n      <td>8.0</td>\n      <td>13.0</td>\n      <td>1.0</td>\n      <td>20.0</td>\n      <td>Premium</td>\n      <td>Annual</td>\n      <td>745.38</td>\n      <td>2.0</td>\n      <td>0.0</td>\n    </tr>\n    <tr>\n      <th>881663</th>\n      <td>26.0</td>\n      <td>Male</td>\n      <td>35.0</td>\n      <td>27.0</td>\n      <td>1.0</td>\n      <td>5.0</td>\n      <td>Standard</td>\n      <td>Quarterly</td>\n      <td>977.31</td>\n      <td>9.0</td>\n      <td>0.0</td>\n    </tr>\n    <tr>\n      <th>881664</th>\n      <td>28.0</td>\n      <td>Male</td>\n      <td>55.0</td>\n      <td>14.0</td>\n      <td>2.0</td>\n      <td>0.0</td>\n      <td>Standard</td>\n      <td>Quarterly</td>\n      <td>602.55</td>\n      <td>2.0</td>\n      <td>0.0</td>\n    </tr>\n    <tr>\n      <th>881665</th>\n      <td>31.0</td>\n      <td>Male</td>\n      <td>48.0</td>\n      <td>20.0</td>\n      <td>1.0</td>\n      <td>14.0</td>\n      <td>Premium</td>\n      <td>Quarterly</td>\n      <td>567.77</td>\n      <td>21.0</td>\n      <td>0.0</td>\n    </tr>\n  </tbody>\n</table>\n<p>707454 rows × 11 columns</p>\n</div>"
			},
			{
				"mimeType": "text/plain",
				"data": "        idade    sexo  tempo_como_cliente  frequencia_uso  \\\n0        30.0  Female                39.0            14.0   \n2        55.0  Female                14.0             4.0   \n5        51.0    Male                33.0            25.0   \n6        58.0  Female                49.0            12.0   \n7        55.0  Female                37.0             8.0   \n...       ...     ...                 ...             ...   \n881661   42.0    Male                54.0            15.0   \n881662   25.0  Female                 8.0            13.0   \n881663   26.0    Male                35.0            27.0   \n881664   28.0    Male                55.0            14.0   \n881665   31.0    Male                48.0            20.0   \n\n        ligacoes_callcenter  dias_atraso assinatura duracao_contrato  \\\n0                       5.0         18.0   Standard           Annual   \n2                       6.0         18.0      Basic        Quarterly   \n5                       9.0         26.0    Premium           Annual   \n6                       3.0         16.0   Standard        Quarterly   \n7                       4.0         15.0    Premium           Annual   \n...                     ...          ...        ...              ...   \n881661                  1.0          3.0    Premium           Annual   \n881662                  1.0         20.0    Premium           Annual   \n881663                  1.0          5.0   Standard        Quarterly   \n881664                  2.0          0.0   Standard        Quarterly   \n881665                  1.0         14.0    Premium        Quarterly   \n\n        total_gasto  meses_ultima_interacao  cancelou  \n0            932.00                    17.0       1.0  \n2            185.00                     3.0       1.0  \n5            129.00                     8.0       1.0  \n6            821.00                    24.0       1.0  \n7            445.00                    30.0       1.0  \n...             ...                     ...       ...  \n881661       716.38                     8.0       0.0  \n881662       745.38                     2.0       0.0  \n881663       977.31                     9.0       0.0  \n881664       602.55                     2.0       0.0  \n881665       567.77                    21.0       0.0  \n\n[707454 rows x 11 columns]"
			}
		]
	},
	{
		"metadata": {
			"outputType": "display_data",
			"transient": {},
			"metadata": {}
		},
		"outputItems": [
			{
				"mimeType": "text/plain",
				"data": "cancelou\n0.0    381666\n1.0    325788\nName: count, dtype: int64"
			}
		]
	},
	{
		"metadata": {
			"outputType": "display_data",
			"transient": {},
			"metadata": {}
		},
		"outputItems": [
			{
				"mimeType": "text/plain",
				"data": "cancelou\n0.0    53.9%\n1.0    46.1%\nName: proportion, dtype: object"
			}
		]
	}
]