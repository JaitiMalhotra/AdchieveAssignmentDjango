# Distance Project

This project calculates the distance from given list of addresses to Adchieve HQ, sorts them and stores in a CSV

## Installation

pip install -r requirements.txt

## Input

Input is a list of name and address of the location.
[
        {
            "name": "Eastern Enterprise B.V.",
            "address": "Deldenerstraat 70, 7551AH Hengelo, The Netherlands"
        },
        {
            "name": "Eastern Enterprise",
            "address": "46/1 Office no 1 Ground Floor , Dada House , Inside dada silk mills compound, Udhana Main Rd, near Chhaydo Hospital, Surat, 394210, India"
        },
        {
            "name": "Adchieve Rotterdam",
            "address": "Weena 505, 3013 AL Rotterdam, The Netherlands"
        },
        {
            "name": "Sherlock Holmes",
            "address": "221B Baker St., London, United Kingdom"
        },
        {
            "name": "The White House",
            "address": "1600 Pennsylvania Avenue, Washington, D.C., USA"
        },
        {
            "name": "The Empire State Building",
            "address": "350 Fifth Avenue, New York City, NY 10118"
        },
        {
            "name": "The Pope",
            "address": "Saint Martha House, 00120 Citta del Vaticano, Vatican City"
        },
        {
            "name": "Neverland",
            "address": "5225 Figueroa Mountain Road, Los Olivos, Calif. 93441, USA"
        }
    ]


## Usage

API for calculating distance is:

/api/v1/distance/

Post the input json of addresses. 

Output will be stored in the Project directory as 'distance.csv'.