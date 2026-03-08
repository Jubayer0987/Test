import time
import re
import requests
from bs4 import BeautifulSoup
import base64
import uuid
import random
import json # Added for License System
from datetime import datetime
from faker import Faker
from rich.console import Console
from rich.panel import Panel
from rich.text import Text
from rich.prompt import Prompt, Confirm
from rich.table import Table
from rich import box
from rich.progress import track
import string
import os
import shutil
import imaplib
import email
from email.header import decode_header
from pathlib import Path
import urllib.request
import sys
import hmac
import hashlib
import threading

#THIS BOT MAKE BY HASAN EXE YOU CAN CHANGE EN>

console = Console()
fake = Faker("ar_SA")

# --- CONFIGURATION ---
CONFIG = {
    "site_url": "https://taxtifree.shop/api/",
