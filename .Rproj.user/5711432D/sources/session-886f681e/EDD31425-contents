# Dans le fichier R/geoCalc.R
#' Calcul du périmètre d'un carré
#'
#' @param cote La longueur d'un côté du carré.
#' @return Le périmètre du carré.
#' @examples
#' perimetre_carre(5)

  #' @param cote La longueur d'un côté du carré (doit être positive).
perimetre_carre <- function(cote) {
    if (cote < 0) {
      stop("La longueur d'un côté doit être positive.")
    }
    return(4 * cote)
  }



#' Calcul de la surface d'un carré
#'
#' @param cote La longueur d'un côté du carré.
#' @return La surface du carré.
#' @examples
#' surface_carre(5)
surface_carre <- function(cote) {
  if (cote < 0) {
    stop("La longueur d'un côté doit être positive.")
  }
  return(cote^2)
}

#' Calcul du périmètre d'un rectangle
#'
#' @param longueur La longueur du rectangle.
#' @param largeur La largeur du rectangle.
#' @return Le périmètre du rectangle.
#' @examples
#' perimetre_rectangle(5, 3)
perimetre_rectangle <- function(longueur, largeur) {
  if (longueur < 0 | largeur<0) {
    stop("La longueur d'un côté doit être positive.")
  }
  return(2 * (longueur + largeur))
}

#' Calcul de la surface d'un rectangle
#'
#' @param longueur La longueur du rectangle.
#' @param largeur La largeur du rectangle.
#' @return La surface du rectangle.
#' @examples
#' surface_rectangle(5, 3)
surface_rectangle <- function(longueur, largeur) {
  if (longueur < 0 | largeur<0) {
    stop("La longueur d'un côté doit être positive.")
  }
  return(longueur * largeur)
}
