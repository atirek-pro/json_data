
{
  "businessName": {
    "type": "string",
    "description": "The official name of the business."
  },
  "businessStage": {
    "type": "string",
    "description": "The stage of the business such as startup, growth, mature, or declining."
  },
  "industry": {
    "type": "string",
    "description": "The industry in which the business operates."
  },
  "productsServices": {
    "type": "array",
    "description": "Detailed description of products or services offered by the business.",
    "items": {
      "type": "string"
    }
  },
  "keyMetrics": {
    "type": "array",
    "description": "Specific KPIs that the business is tracking.",
    "items": {
      "type": "string"
    }
  },
  "businessGoals": {
    "type": "array",
    "description": "Short and long term business objectives.",
    "items": {
      "type": "string"
    }
  }
}


 

{
  "financialData": {
    "type": "object",
    "description": "Financial statements and financial ratios.",
    "properties": {
      "statements": {
        "type": "string"
      },
      "ratios": {
        "type": "string"
      }
    }
  },
  "businessPlans": {
    "type": "string",
    "description": "Future plans and strategies of the business."
  },
  "pricing": {
    "type": "string",
    "description": "Pricing strategies and details for the products or services."
  },
  "marketPositioning": {
    "type": "string",
    "description": "How the business positions itself within the industry."
  },
  "competitiveAnalysis": {
    "type": "string",
    "description": "Detailed analysis of main competitors."
  },
  "businessModel": {
    "type": "string",
    "description": "Details of how the business generates revenue."
  },
  "targetMarket": {
    "type": "string",
    "description": "Description of the business's target customers."
  }
}



 


{
  "legalStructure": {
    "type": "string",
    "description": "The legal form of the business (e.g., LLC, Corporation, etc.)."
  },
  "fundingInformation": {
    "type": "string",
    "description": "Details about past rounds of funding and future funding needs."
  },
  "businessLocations": {
    "type": "array",
    "description": "Information about the physical location(s) of the business.",
    "items": {
      "type": "string"
    }
  },
  "currentMarketingStrategies": {
    "type": "string",
    "description": "Overview of the business's current marketing strategies."
  },
  "technologyStack": {
    "type": "string",
    "description": "Information about the key technologies used in the business."
  },
  "businessHistory": {
    "type": "string",
    "description": "Brief history of the business including significant events."
  },
  "keyPersonnel": {
    "type": "array",
    "description": "Brief bios of key personnel and their roles.",
    "items": {
      "type": "string"
    }
  }
}

Claude Update v2 (M&A)

 

{
  "companyOverview": {
    "type": "object", 
    "properties": {
      
      "organizationalStructure": {
        "type": "string",
        "description": "Overview of company structure and departments"
      },
      
      "numEmployees": {
        "type": "integer",
        "description": "Total number of employees"
      },
      
      "competitiveAdvantages": {
        "type": "array", 
        "items": {
          "type": "string"
        },
        "description": "List of factors that give the company an edge over competitors"
      }
      
    }
  },

  "industryOverview": {
    "type": "object", 
    "properties": {
    
      "competitiveLandscape": {
        "type": "string",
        "description": "Analysis of key competitors in the industry"
      }
      
    }
  },
  
  "businessDescription": {
    "type": "object",
    "properties": {

      "targetCustomers": {
        "type": "array",
        "items": {
          "type": "string" 
        },
        "description": "List of target customer personas"
      },

      "salesProcess": {
        "type": "string",
        "description": "Description of sales process and cycle"
      },

      "strategicPartners": {
        "type": "array",
        "items": {
          "type": "string"
        },
        "description": "List of key strategic partnerships"
      },

      "marketingStrategy": {
        "type": "string",
        "description": "Overview of current marketing strategies and channels"
      }

    }
  },

  "operations": {
    "type": "object",
    "properties": {
    
      "operationalProcesses": {
        "type": "string",
        "description": "Overview of key operational processes"
      },

      "technologyAndSystems": {
        "type": "string", 
        "description": "Description of technologies and systems used"
      },

      "intellectualProperty": {
        "type": "string",
        "description": "Overview of patents, trademarks, copyrights held"
      },

      "researchAndDevelopment": {
        "type": "string",
        "description": "Details on research and development activities"
      }
      
    }
  },

  "facilities": {
    "type": "object",
    "properties": {

      "warehouses": {
        "type": "array",
        "items": {
          "type": "string"  
        },
        "description": "List of warehouse locations"
      },

      "manufacturingPlants": {
        "type": "array",
        "items": {
          "type": "string"
        },
        "description": "List of manufacturing and production facilities"
      },

      "conditionOfAssets": {
        "type": "string",
        "description": "Overview of general condition and value of physical assets"
      }

    }
  },

  "growthOpportunities": {
    "type": "object", 
    "properties": {

      "expansionPlans": {
        "type": "string",
        "description": "Details on plans for future expansion"  
      },

      "newProductsServices": {
        "type": "array",
        "items": {
          "type": "string"
        },
        "description": "List of new products and services under development"
      }

    }
  }

}

