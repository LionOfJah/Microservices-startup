package io.javadems.service.resource;

import java.util.Collections;
import java.util.List;

import org.springframework.web.bind.annotation.PathVariable;
import org.springframework.web.bind.annotation.RequestMapping;
import org.springframework.web.bind.annotation.RestController;

import io.javadems.service.model.CatalogItem;

@RestController
@RequestMapping("/catalog")
public class MovieCatalogueResource {

	@RequestMapping("/{userId}")
	public List<CatalogItem> getCatalog(@PathVariable String userId){
		
		return Collections.singletonList(
				new CatalogItem("Transformers", "Test", 4)); 
	};
}
