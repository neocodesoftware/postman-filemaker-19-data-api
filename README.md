best thing

"name": "Authenticate",
			"event": [
				{
					"listen": "test",
					"script": {
						"exec": [
							"var jsonData = JSON.parse(responseBody);",
							"postman.setEnvironmentVariable(\"FMAPIToken\", jsonData.response.token)"


fork of

https://msdev.nz/introduction-to-the-filemaker-data-api-scandanavia-devcon/


filemaker 19 data api

https://fmhelp.filemaker.com/fm19/en/data-api-guide/content/index.html

https://fmhelp.filemaker.com/fm19/en/data-api-guide/content/get-range-of-records.html



archive

https://community.claris.com/en/s/question/0D50H00006o6akGSAQ/does-anyone-have-an-updated-postman-collection-for-filemaker-18s-data-api

https://www.soliantconsulting.com/blog/filemaker-data-api-server-16/

https://github.com/myFMbutler/fm-data-api-19-postman
