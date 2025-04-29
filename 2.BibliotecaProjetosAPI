function Fase(portfolio) {
  //var planilha = SpreadsheetApp.getActiveSpreadsheet().getSheetByName('Projetos API')
 // var ultimalinha = planilha.getLastRow()
  //var fases1 = planilha.getRange(2,4,ultimalinha-1,1).getValues()

  if (portfolio == "fase 01") {
    return('F01')
  }
  else {
    if (portfolio == "fase 02") {
      return('F02')
    }
    else {
      if (portfolio == "fase 03") {
        return('F03')
      }
      else {
        if (portfolio == "fase 04") {
          return('F04')
        }
        else {
          return('0')
        }
      }
    }
  }
}

function GetCustomField(data,fieldName) {
  var value = null
  for (var f = 0; f < Object.keys(data.custom_fields).length; f++){
    if (data.custom_fields[f].name == fieldName)
      try{
        value = data.custom_fields[f].value
      }
      catch (e){
      };
  };
  return value
}
