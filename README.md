# Software-FJ
Ejercicio 1: Sistema Integral de Gestión de Clientes, Servicios y Reservas
=========================================================
                  PROYECTO SOFTWARE FJ
       SISTEMA INTEGRAL DE GESTIÓN DE CLIENTES,
                SERVICIOS Y RESERVAS
=========================================================

Presentado por:
1. Alfonso Enrique Anaya Barbosa
2. Solano Ortega Jahleel Uzai

Programa:
Ingeniería Electrónica

Universidad:
Universidad Nacional Abierta y a Distancia - UNAD

Lenguaje de programación:
Python

Proyecto académico:
Desarrollo de Software FJ

=========================================================
"""

from datetime import datetime, timedelta

from gestion import GestorSistema
from clientes import Cliente

from servicios import (
    ReservaSala,
    AlquilerEquipo,
    Asesoria
)

from excepciones import ErrorSistema
from gestor_logs import logger


def mostrar_presentacion():

    print("\n")
    print("=" * 60)
    print("                 PROYECTO SOFTWARE FJ")
    print("=" * 60)

    print("SISTEMA INTEGRAL DE GESTIÓN DE CLIENTES,")
    print("SERVICIOS Y RESERVAS")

    print("-" * 60)

    print("PRESENTADO POR:")
    print("1. Alfonso Enrique Anaya Barbosa")
    print("2. Solano Ortega Jahleel Uzai")

    print("\nPrograma:")
    print("Ingeniería Electrónica")

    print("\nUniversidad:")
    print("Universidad Nacional Abierta y a Distancia - UNAD")

    print("\nLenguaje de programación:")
    print("Python")

    print("\nModalidad:")
    print("Trabajo colaborativo")

    print("=" * 60)

    input("\nPresione ENTER para ingresar al sistema...")
